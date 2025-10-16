<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 插入Facebook域名验证meta标签 -->
    <meta name="facebook-domain-verification" content="8ljpq1tooa23sf0fc15thsjlguvdns" />
    <title>极简个人博客</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#2563eb',
                        secondary: '#64748b',
                        dark: '#0f172a'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans text-gray-800">
    <!-- 导航栏 -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            极简博客
            <nav class="hidden md:flex space-x-6">
                首页
                文章
                关于
            </nav>
            <button class="md:hidden text-gray-600">
                <<i class="fa fa-bars text-xl"></</i>
            </button>
        </div>
    </header>

    <!-- 主内容区 -->
    <main class="container mx-auto px-4 py-8 grid grid-cols-1 lg:grid-cols-3 gap-8">
        <!-- 文章列表 -->
        <section class="lg:col-span-2">
            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-8 transition-transform hover:scale-[1.01]">
                <div class="p-6">
                    <h2 class="text-2xl font-bold mb-4 text-dark">创意DIY：绿巨人造型的电脑主机</h2>
                    <div class="mb-4 text-gray-500 flex items-center">
                        <span><<i class="fa fa-calendar-o mr-2"></</i>2025-10-17</span>
                        <span class="ml-4"><<i class="fa fa-tag mr-2"></</i>DIY硬件</span>
                    </div>
                    <!-- 插入目标图片 -->
                    <div class="mb-6">
                        < img src="https://example.com/hulk-pc.jpg" alt="绿巨人造型的DIY电脑主机" class="w-full h-auto rounded-lg object-cover shadow-sm">
                        <p class="text-sm text-gray-500 mt-2 italic">图：用绿巨人模型改造的创意电脑主机，集成了主板、显卡、电源等硬件</p >
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        这是一款极具创意的DIY电脑主机：以绿巨人模型为载体，将主板、显卡、散热器、电源等硬件直接“搭载”在模型上，既保留了硬件的功能性，又通过漫威角色的造型增加了趣味性，是硬件爱好者与动漫粉丝的创意结合作品。
                    </p >
                    <a href="#" class="inline-block text-primary font-medium hover:underline">
                        阅读全文 <<i class="fa fa-arrow-right ml-1"></</i>
                    </a >
                </div>
            </article>

            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-8">
                <div class="p-6">
                    <h2 class="text-2xl font-bold mb-4 text-dark">普通电脑主机的装机指南</h2>
                    <div class="mb-4 text-gray-500 flex items-center">
                        <span><<i class="fa fa-calendar-o mr-2"></</i>2025-10-15</span>
                        <span class="ml-4"><<i class="fa fa-tag mr-2"></</i>装机教程</span>
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        相比创意主机，普通装机更注重稳定性与兼容性。本文将介绍从硬件选择到组装调试的完整流程，帮助新手快速完成一台实用的电脑主机...
                    </p >
                    <a href="#" class="inline-block text-primary font-medium hover:underline">
                        阅读全文 <<i class="fa fa-arrow-right ml-1"></</i>
                    </a >
                </div>
            </article>
        </section>

        <!-- 侧边栏 -->
        <aside class="lg:col-span-1">
            <div class="bg-white rounded-lg shadow-md p-6 mb-8">
                <h3 class="text-xl font-bold mb-4 text-dark border-b pb-2">热门标签</h3>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1 bg-blue-50 text-primary rounded-full text-sm">DIY硬件</span>
                    <span class="px-3 py-1 bg-blue-50 text-primary rounded-full text-sm">装机教程</span>
                    <span class="px-3 py-1 bg-blue-50 text-primary rounded-full text-sm">创意改造</span>
                    <span class="px-3 py-1 bg-blue-50 text-primary rounded-full text-sm">电脑硬件</span>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-md p-6">
                <h3 class="text-xl font-bold mb-4 text-dark border-b pb-2">关于博主</h3>
                <p class="text-gray-700 leading-relaxed">
                    硬件爱好者，喜欢DIY各类创意电子设备，分享装机、改造的经验与趣事。
                </p >
            </div>
        </aside>
    </main>

    <!-- 页脚 -->
    <footer class="bg-dark text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p class="mb-4">极简个人博客 &copy; 2025 版权所有</p >
            <div class="flex justify-center space-x-4">
                <<i class="fa fa-github text-xl"></</i>
                <<i class="fa fa-weibo text-xl"></</i>
            </div>
        </div>
    </footer>
</body>
</html>
