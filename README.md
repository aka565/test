# test
<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>魔幻世界 - 一款史诗级 RPG 游戏</title>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<script>
tailwind.config = {
theme: {
extend: {
colors: {
primary: '#6366f1',
secondary: '#4f46e5'
},
borderRadius: {
'none': '0px',
'sm': '2px',
DEFAULT: '4px',
'md': '8px',
'lg': '12px',
'xl': '16px',
'2xl': '20px',
'3xl': '24px',
'full': '9999px',
'button': '4px'
}
}
}
}
</script>
<style>
body {
min-height: 1024px;
}
.hero-section {
background-image: url('https://ai-public.mastergo.com/ai/img_res/b6d34546b6eabc959025f108e57655c9.jpg');
background-size: cover;
background-position: center;
}
.screenshot-container::-webkit-scrollbar {
display: none;
}
</style>
</head>
<body class="bg-gray-900 text-white">
<nav class="fixed w-full bg-gray-900/80 backdrop-blur-md z-50">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex items-center justify-between h-16">
<div class="flex items-center">
<span class="text-2xl font-['Pacifico'] text-white">logo</span>
<div class="ml-10 flex items-baseline space-x-8">
<a href="#intro" class="text-gray-300 hover:text-white px-3 py-2">游戏介绍</a>
<a href="#features" class="text-gray-300 hover:text-white px-3 py-2">特色玩法</a>
<a href="#screenshots" class="text-gray-300 hover:text-white px-3 py-2">游戏截图</a>
<a href="#download" class="text-gray-300 hover:text-white px-3 py-2">下载体验</a>
</div>
</div>
</div>
</div>
</nav>
<section class="hero-section h-[600px] flex items-center relative">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
<div class="max-w-2xl">
<h1 class="text-5xl font-bold mb-4">魔幻世界</h1>
<p class="text-xl mb-8">探索浩瀚魔法世界，成为传奇英雄。在这个史诗般的 RPG 游戏中，你将踏上一段惊心动魄的冒险之旅。</p>
<button class="bg-primary hover:bg-secondary text-white px-8 py-3 !rounded-button whitespace-nowrap text-lg font-semibold transition-colors">
立即体验
</button>
</div>
</div>
<div class="absolute inset-0 bg-gradient-to-r from-gray-900/80 to-transparent"></div>
</section>
<section id="features" class="py-20 bg-gray-800">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-16">游戏特色</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
<div class="bg-gray-700 p-6 rounded-lg hover:transform hover:scale-105 transition-transform">
<div class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center mb-4">
<i class="fas fa-dragon text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">史诗剧情</h3>
<p class="text-gray-300">沉浸式的故事体验，让你在精心编织的剧情中感受史诗般的冒险。</p>
</div>
<div class="bg-gray-700 p-6 rounded-lg hover:transform hover:scale-105 transition-transform">
<div class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center mb-4">
<i class="fas fa-wand-sparkles text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">魔法系统</h3>
<p class="text-gray-300">独特的魔法组合系统，创造属于你的战斗风格。</p>
</div>
<div class="bg-gray-700 p-6 rounded-lg hover:transform hover:scale-105 transition-transform">
<div class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center mb-4">
<i class="fas fa-users text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">多人冒险</h3>
<p class="text-gray-300">与好友组队探索广阔世界，共同挑战史诗级副本。</p>
</div>
<div class="bg-gray-700 p-6 rounded-lg hover:transform hover:scale-105 transition-transform">
<div class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center mb-4">
<i class="fas fa-gem text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">装备系统</h3>
<p class="text-gray-300">丰富的装备打造系统，打造专属于你的完美装备。</p>
</div>
</div>
</div>
</section>
<section id="screenshots" class="py-20 bg-gray-900">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-16">游戏截图</h2>
<div class="relative">
<div class="screenshot-container flex space-x-4 overflow-x-auto pb-4">
<div class="flex-none w-[600px]">
<img src="https://ai-public.mastergo.com/ai/img_res/02bca93a0a79fa5b77f8f2a249ba849a.jpg" class="rounded-lg" alt="游戏截图1">
<p class="mt-2 text-gray-400">史诗级魔法对决</p>
</div>
<div class="flex-none w-[600px]">
<img src="https://ai-public.mastergo.com/ai/img_res/a14d0b830237c41f208156fecd773064.jpg" class="rounded-lg" alt="游戏截图2">
<p class="mt-2 text-gray-400">神秘的魔法村庄</p>
</div>
<div class="flex-none w-[600px]">
<img src="https://ai-public.mastergo.com/ai/img_res/c112e508984fda094caef725c3eb4746.jpg" class="rounded-lg" alt="游戏截图3">
<p class="mt-2 text-gray-400">史诗级巨龙战斗</p>
</div>
</div>
</div>
</div>
</section>
<section id="download" class="py-20 bg-gray-800">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
<h2 class="text-3xl font-bold mb-8">立即下载</h2>
<div class="flex justify-center space-x-8 mb-12">
<a href="https://magicworld.com/download/windows" class="bg-primary hover:bg-secondary text-white px-8 py-3 !rounded-button whitespace-nowrap flex items-center">
<i class="fab fa-windows mr-2"></i>
Windows 版本
</a>
<a href="https://magicworld.com/download/macos" class="bg-primary hover:bg-secondary text-white px-8 py-3 !rounded-button whitespace-nowrap flex items-center">
<i class="fab fa-apple mr-2"></i>
MacOS 版本
</a>
</div>
<div class="bg-gray-700 p-6 rounded-lg inline-block">
<h3 class="text-xl font-semibold mb-4">系统配置要求</h3>
<div class="text-left space-y-2 text-gray-300">
<p>操作系统：Windows 10 64位</p>
<p>处理器：Intel i5-6600K 或 AMD Ryzen 5 2600X</p>
<p>内存：16 GB RAM</p>
<p>显卡：NVIDIA GTX 1660 或 AMD RX 5600 XT</p>
<p>存储空间：100 GB 可用空间</p>
</div>
</div>
</div>
</section>
<footer class="bg-gray-900 py-12">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8">
<div>
<span class="text-2xl font-['Pacifico'] text-white">logo</span>
<p class="mt-2 text-gray-400">打造属于你的魔幻世界</p>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">关注我们</h3>
<div class="flex space-x-4">
<a href="#" class="text-gray-400 hover:text-white">
<i class="fab fa-weibo text-xl"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<i class="fab fa-weixin text-xl"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<i class="fab fa-qq text-xl"></i>
</a>
</div>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">联系我们</h3>
<p class="text-gray-400">客服邮箱：support@magicworld.com</p>
<p class="text-gray-400">商务合作：business@magicworld.com</p>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">法律信息</h3>
<p class="text-gray-400">游戏著作权所有 © 2023</p>
<p class="text-gray-400">文网游备字[2023] M-RPG 号</p>
</div>
</div>
<div class="mt-8 pt-8 border-t border-gray-800 text-center text-gray-400">
<p>Copyright © 2023 魔幻世界. All rights reserved.</p>
</div>
</div>
</footer>
</body>
</html>
