<html lang="zh-CN"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>区域销售经理（中国区）- 吴泽鸿个人简历</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0f3460',
                        secondary: '#e94560',
                        accent: '#ff9800',
                        dark: '#1a1a2e',
                        light: '#f5f5f7'
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
            .text-shadow {
                text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
            }
            .section-fade {
                opacity: 0;
                transform: translateY(20px);
                transition: opacity 0.6s ease-out, transform 0.6s ease-out;
            }
            .section-visible {
                opacity: 1;
                transform: translateY(0);
            }
            .progress-bar {
                height: 8px;
                background-color: #e2e8f0;
                border-radius: 4px;
                overflow: hidden;
            }
            .progress-value {
                height: 100%;
                background-color: #ff9800;
                border-radius: 4px;
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans text-gray-800">
    <!-- 导航栏 -->
    <nav class="bg-primary text-white shadow-md fixed w-full z-50 transition-all duration-300" id="navbar">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa fa-briefcase text-accent text-2xl"></i>
                <span class="font-bold text-xl">吴泽鸿简历</span>
            </div>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#home" class="hover:text-accent transition-colors duration-200">首页</a>
                <a href="#experience" class="hover:text-accent transition-colors duration-200">工作经验</a>
                <a href="#projects" class="hover:text-accent transition-colors duration-200">项目经验</a>
                <a href="#skills" class="hover:text-accent transition-colors duration-200">专业技能</a>
                <a href="#education" class="hover:text-accent transition-colors duration-200">教育背景</a>
                <a href="#contact" class="bg-accent hover:bg-accent/80 text-white px-4 py-2 rounded-md transition-all duration-200 transform hover:scale-105">联系我</a>
            </div>
            <button class="md:hidden text-white focus:outline-none" id="menuToggle">
                <i class="fa fa-bars text-xl"></i>
            </button>
        </div>
        <!-- 移动端菜单 -->
        <div class="md:hidden hidden bg-primary/95 absolute w-full" id="mobileMenu">
            <div class="container mx-auto px-4 py-3 flex flex-col space-y-3">
                <a href="#home" class="hover:text-accent py-2 transition-colors duration-200">首页</a>
                <a href="#experience" class="hover:text-accent py-2 transition-colors duration-200">工作经验</a>
                <a href="#projects" class="hover:text-accent py-2 transition-colors duration-200">项目经验</a>
                <a href="#skills" class="hover:text-accent py-2 transition-colors duration-200">专业技能</a>
                <a href="#education" class="hover:text-accent py-2 transition-colors duration-200">教育背景</a>
                <a href="#contact" class="bg-accent hover:bg-accent/80 text-white px-4 py-2 rounded-md text-center transition-all duration-200">联系我</a>
            </div>
        </div>
    </nav>

    <!-- 英雄区域 -->
    <header id="home" class="pt-24 pb-16 bg-gradient-to-br from-primary to-dark text-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <div class="relative">
                        <div class="w-64 h-64 rounded-full overflow-hidden border-4 border-accent shadow-lg mx-auto md:mx-0 transform transition-transform duration-500 hover:scale-105">
                            <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/code_assistant/311c3895309442e59a888c80f95e21b3~tplv-a9rns2rl98-image.image?rcl=202509011603544196DB47147D1F8088DA&amp;rk3s=8e244e95&amp;rrcfp=e75484ac&amp;x-expires=1757318640&amp;x-signature=GcZE0%2F%2FBXKqtCFApLeji%2Ftwt1KM%3D" alt="吴泽鸿照片" class="w-full h-full object-cover">
                        </div>
                        <div class="absolute -bottom-3 -right-3 bg-accent text-white rounded-full w-16 h-16 flex items-center justify-center shadow-md">
                            <span class="font-bold text-center">5+年<br>经验</span>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 md:pl-10">
                    <h1 class="text-[clamp(2rem,5vw,3.5rem)] font-bold leading-tight text-shadow mb-4">
                        吴泽鸿 <span class="text-accent">项目管理专家</span>
                    </h1>
                    <h2 class="text-[clamp(1.2rem,3vw,1.8rem)] text-gray-200 mb-6">
                        应聘：区域销售经理（中国区）
                    </h2>
                    <p class="text-gray-300 text-lg mb-8 max-w-lg">
                        拥有5年以上项目管理与市场拓展经验，擅长团队协作、市场分析与策略制定，具备出色的沟通协调能力和数据分析能力，成功主导多个项目并取得显著成果。
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#contact" class="bg-accent hover:bg-accent/90 text-white px-6 py-3 rounded-md font-medium transition-all duration-300 transform hover:scale-105 flex items-center">
                            <i class="fa fa-paper-plane mr-2"></i> 立即联系
                        </a>
                        <a href="#experience" class="bg-white/10 hover:bg-white/20 backdrop-blur-sm text-white border border-white/30 px-6 py-3 rounded-md font-medium transition-all duration-300 flex items-center">
                            <i class="fa fa-briefcase mr-2"></i> 查看经验
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- 基本信息 -->
    <section class="py-10 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-5 gap-6">
                <div class="bg-light rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300 flex items-start">
                    <div class="bg-primary/10 p-3 rounded-full mr-4">
                        <i class="fa fa-user text-primary text-xl"></i>
                    </div>
                    <div>
                        <h3 class="font-semibold text-lg mb-1">基本信息</h3>
                        <p class="text-gray-600">汉族 | 2000.04.13</p>
                    </div>
                </div>
                <div class="bg-light rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300 flex items-start">
                    <div class="bg-primary/10 p-3 rounded-full mr-4">
                        <i class="fa fa-map-marker text-primary text-xl"></i>
                    </div>
                    <div>
                        <h3 class="font-semibold text-lg mb-1">所在地</h3>
                        <p class="text-gray-600">广东广州</p>
                        <p class="text-gray-500 text-sm">籍贯：广东揭阳</p>
                    </div>
                </div>
                <div class="bg-light rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300 flex items-start">
                    <div class="bg-primary/10 p-3 rounded-full mr-4">
                        <i class="fa fa-phone text-primary text-xl"></i>
                    </div>
                    <div>
                        <h3 class="font-semibold text-lg mb-1">电话</h3>
                        <p class="text-gray-600">15360401565</p>
                    </div>
                </div>
                <div class="bg-light rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300 flex items-start">
                    <div class="bg-primary/10 p-3 rounded-full mr-4">
                        <i class="fa fa-envelope text-primary text-xl"></i>
                    </div>
                    <div>
                        <h3 class="font-semibold text-lg mb-1">邮箱</h3>
                        <p class="text-gray-600">870599702@qq.com</p>
                    </div>
                </div>
                <div class="bg-light rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300 flex items-start">
                    <div class="bg-primary/10 p-3 rounded-full mr-4">
                        <i class="fa fa-briefcase text-primary text-xl"></i>
                    </div>
                    <div>
                        <h3 class="font-semibold text-lg mb-1">求职意向</h3>
                        <p class="text-gray-600">区域销售经理</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 工作经验 -->
    <section id="experience" class="py-16 bg-gray-50 section-fade">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold text-primary mb-4">工作经验</h2>
                <div class="w-20 h-1 bg-accent mx-auto mb-6"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">丰富的项目管理、市场拓展和团队协作经验，具备出色的沟通协调能力和问题解决能力</p>
            </div>

            <div class="relative">
                <!-- 时间线 -->
                <div class="hidden md:block absolute left-1/2 top-0 bottom-0 w-1 bg-gray-200 transform -translate-x-1/2"></div>
                
                <!-- 经验1 -->
                <div class="mb-12 relative">
                    <div class="md:flex items-center">
                        <div class="md:w-1/2 md:pr-12 md:text-right mb-6 md:mb-0">
                            <span class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-sm font-medium mb-3">2024.10 - 2024.11</span>
                            <h3 class="text-xl font-bold mb-2">广东财经大学校团委三助一辅助管</h3>
                            <p class="text-accent font-medium mb-3">行政与项目管理</p>
                            <ul class="text-gray-600 space-y-2 md:ml-auto md:max-w-md">
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">负责日常事务处理、文件归档与数据统计</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">撰写会议纪要、活动筹备与行政支持</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">优化办公流程，提升团队工作效率20%</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                            </ul>
                        </div>
                        <div class="hidden md:block absolute left-1/2 w-6 h-6 rounded-full bg-accent transform -translate-x-1/2 shadow-lg"></div>
                        <div class="md:w-1/2 md:pl-12">
                            <div class="hidden md:block h-full bg-gray-100 rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300">
                                <div class="flex items-center mb-4">
                                    <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fa fa-cogs text-primary text-xl"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">主要职责</h4>
                                        <p class="text-sm text-gray-500">行政协调与项目支持</p>
                                    </div>
                                </div>
                                <p class="text-gray-600 text-sm">负责组织协调各类会议和活动，管理文档资料，提供全面行政支持，确保团队高效运作。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 经验2 -->
                <div class="mb-12 relative">
                    <div class="md:flex items-center">
                        <div class="md:w-1/2 md:pr-12 order-1 md:order-1">
                            <div class="hidden md:block h-full bg-gray-100 rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300">
                                <div class="flex items-center mb-4">
                                    <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fa fa-line-chart text-primary text-xl"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">销售成果</h4>
                                        <p class="text-sm text-gray-500">外贸业务拓展</p>
                                    </div>
                                </div>
                                <p class="text-gray-600 text-sm">通过优化产品展示和SEO策略，显著提升产品曝光率和转化率，为公司创造了可观的销售增长。</p>
                            </div>
                        </div>
                        <div class="hidden md:block absolute left-1/2 w-6 h-6 rounded-full bg-accent transform -translate-x-1/2 shadow-lg"></div>
                        <div class="md:w-1/2 md:pl-12 mb-6 md:mb-0 order-0 md:order-2">
                            <span class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-sm font-medium mb-3">2024.06 - 2024.08</span>
                            <h3 class="text-xl font-bold mb-2">外贸业务员</h3>
                            <p class="text-accent font-medium mb-3">佛山耐斯登医疗器械有限公司</p>
                            <ul class="text-gray-600 space-y-2">
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>参与贸易采购洽谈，推动外贸板块当月销售量突破200</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>助力企业团队新增店铺，新店在中国制造网初日收获1w+流量</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>为企业三只热销产品拍摄宣传视频，发布于抖音，反响良好</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>负责平台运营、产品知识学习、SEO优化及行业分析</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- 经验3 -->
                <div class="mb-12 relative">
                    <div class="md:flex items-center">
                        <div class="md:w-1/2 md:pr-12 md:text-right mb-6 md:mb-0">
                            <span class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-sm font-medium mb-3">2024.03 - 2024.06</span>
                            <h3 class="text-xl font-bold mb-2">人力资源实习生</h3>
                            <p class="text-accent font-medium mb-3">广财大单位资产公司</p>
                            <ul class="text-gray-600 space-y-2 md:ml-auto md:max-w-md">
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">承担项目策划、行政支持、文档编写与数据分析</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">负责公文撰写及财务管理辅助工作</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">参与制定公司人力资源管理流程与规范</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                            </ul>
                        </div>
                        <div class="hidden md:block absolute left-1/2 w-6 h-6 rounded-full bg-accent transform -translate-x-1/2 shadow-lg"></div>
                        <div class="md:w-1/2 md:pl-12">
                            <div class="hidden md:block h-full bg-gray-100 rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300">
                                <div class="flex items-center mb-4">
                                    <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fa fa-users text-primary text-xl"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">主要贡献</h4>
                                        <p class="text-sm text-gray-500">流程优化与团队支持</p>
                                    </div>
                                </div>
                                <p class="text-gray-600 text-sm">通过系统化整理人力资源文档和优化招聘流程，使新员工入职培训效率提升30%，得到部门领导高度认可。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 经验4 -->
                <div class="mb-12 relative">
                    <div class="md:flex items-center">
                        <div class="md:w-1/2 md:pr-12 order-1 md:order-1">
                            <div class="hidden md:block h-full bg-gray-100 rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300">
                                <div class="flex items-center mb-4">
                                    <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fa fa-search text-primary text-xl"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">研究成果</h4>
                                        <p class="text-sm text-gray-500">产业分析与策略建议</p>
                                    </div>
                                </div>
                                <p class="text-gray-600 text-sm">研究成果为广州智慧旅游产业链发展提供了有价值的参考，部分建议被相关部门采纳实施。</p>
                            </div>
                        </div>
                        <div class="hidden md:block absolute left-1/2 w-6 h-6 rounded-full bg-accent transform -translate-x-1/2 shadow-lg"></div>
                        <div class="md:w-1/2 md:pl-12 mb-6 md:mb-0 order-0 md:order-2">
                            <span class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-sm font-medium mb-3">2023.11 - 2023.12</span>
                            <h3 class="text-xl font-bold mb-2">研究助理研究员</h3>
                            <p class="text-accent font-medium mb-3">广州智慧旅游课题</p>
                            <ul class="text-gray-600 space-y-2">
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>负责文献查阅、实地走访、图谱绘制与企业梳理</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>进行案例总结及内容校对，形成专业研究报告</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>分析产业链上中下游产业集聚、规模与竞争力</span>
                                </li>
                                <li class="flex items-center">
                                    <i class="fa fa-check-circle text-accent mr-2"></i>
                                    <span>提出举措和对策建议，助力健全现代文旅产业体系</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- 经验5 -->
                <div class="relative">
                    <div class="md:flex items-center">
                        <div class="md:w-1/2 md:pr-12 md:text-right mb-6 md:mb-0">
                            <span class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-sm font-medium mb-3">2023.03 - 2023.06</span>
                            <h3 class="text-xl font-bold mb-2">助理编辑</h3>
                            <p class="text-accent font-medium mb-3">广东教育杂志社《职教版》</p>
                            <ul class="text-gray-600 space-y-2 md:ml-auto md:max-w-md">
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">负责策划编审、分配任务、催审修稿与定版印刷</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">检查邮寄及记录反馈，确保刊物质量与发行效率</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                                <li class="flex items-center md:justify-end">
                                    <span class="md:order-2">前往韶关市仁化中学开展"双新"主题调研与采访</span>
                                    <i class="fa fa-check-circle text-accent mr-2 md:mr-0 md:ml-2 md:order-1"></i>
                                </li>
                            </ul>
                        </div>
                        <div class="hidden md:block absolute left-1/2 w-6 h-6 rounded-full bg-accent transform -translate-x-1/2 shadow-lg"></div>
                        <div class="md:w-1/2 md:pl-12">
                            <div class="hidden md:block h-full bg-gray-100 rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow duration-300">
                                <div class="flex items-center mb-4">
                                    <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fa fa-edit text-primary text-xl"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">突出表现</h4>
                                        <p class="text-sm text-gray-500">专题策划与执行</p>
                                    </div>
                                </div>
                                <p class="text-gray-600 text-sm">成功策划并执行"双新"教育改革专题报道，获得读者广泛好评，该期杂志发行量同比增长15%。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 项目经验 -->
    <section id="projects" class="py-16 bg-white section-fade">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold text-primary mb-4">项目经验</h2>
                <div class="w-20 h-1 bg-accent mx-auto mb-6"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">作为项目负责人，成功主导多个重要项目，具备出色的项目规划、执行与管理能力</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- 项目1 -->
                <div class="bg-light rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-48 overflow-hidden">
                        <img src="https://picsum.photos/id/1043/600/400" alt="壮瑶人家-宠物友好民宿项目" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <span class="bg-primary/10 text-primary px-3 py-1 rounded-full text-sm">2023年</span>
                            <span class="text-gray-500 text-sm">项目负责人</span>
                        </div>
                        <h3 class="text-xl font-bold mb-3">壮瑶人家-宠物友好民宿助推乡村产业高质量发展</h3>
                        <p class="text-gray-600 mb-4">该项目旨在通过开发宠物友好型民宿，结合乡村特色资源，推动乡村旅游产业升级，实现乡村振兴与产业高质量发展。</p>
                        <div class="mb-4">
                            <h4 class="font-semibold mb-2">我的职责：</h4>
                            <ul class="text-gray-600 space-y-1 text-sm">
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>负责项目整体策划与团队协调管理</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>开展市场调研与目标客户群体分析</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>制定营销策略与运营方案</span>
                                </li>
                            </ul>
                        </div>
                        <div>
                            <h4 class="font-semibold mb-2">项目成果：</h4>
                            <p class="text-gray-600 text-sm">获大学生创业大赛校赛银奖，形成可复制的乡村旅游产业升级模式，得到当地政府关注与支持。</p>
                        </div>
                    </div>
                </div>

                <!-- 项目2 -->
                <div class="bg-light rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-48 overflow-hidden">
                        <img src="https://picsum.photos/id/131/600/400" alt="以竹代塑--惠州市龙门县产业转型升级项目" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <span class="bg-primary/10 text-primary px-3 py-1 rounded-full text-sm">2023年12月</span>
                            <span class="text-gray-500 text-sm">项目主持人</span>
                        </div>
                        <h3 class="text-xl font-bold mb-3">以竹代塑--惠州市龙门县产业转型升级助力乡村振兴</h3>
                        <p class="text-gray-600 mb-4">该项目旨在推动惠州市龙门县竹制品产业升级，开发环保竹制替代塑料制品，促进产业转型与乡村经济发展。</p>
                        <div class="mb-4">
                            <h4 class="font-semibold mb-2">我的职责：</h4>
                            <ul class="text-gray-600 space-y-1 text-sm">
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>担任项目主持人，负责项目整体规划与执行</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>协调政府、企业与研究机构资源，建立合作机制</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fa fa-angle-right text-accent mt-1 mr-2"></i>
                                    <span>组织开展市场分析与产品定位研究</span>
                                </li>
                            </ul>
                        </div>
                        <div>
                            <h4 class="font-semibold mb-2">项目成果：</h4>
                            <p class="text-gray-600 text-sm">获省级项目立项并良好结项，为当地创造了新的经济增长点，带动50余户农户增收。</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 早期项目经验 -->
            <div class="mt-10 bg-gray-50 rounded-lg p-6">
                <h3 class="text-xl font-bold mb-6 flex items-center">
                    <i class="fa fa-history text-accent mr-3"></i>
                    早期项目经验
                </h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-5 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h4 class="font-semibold mb-2">自媒体策划与执行</h4>
                        <p class="text-sm text-gray-500 mb-2">2019.09 - 2019.12</p>
                        <p class="text-gray-600 text-sm">担任自媒体策划团队主持，负责撰写脚本、文学剧本、策划广告及拍摄投放，成功完成多个宣传短片和广告项目。</p>
                    </div>
                    <div class="bg-white p-5 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h4 class="font-semibold mb-2">地方宣传短片制作</h4>
                        <p class="text-sm text-gray-500 mb-2">2019年8月</p>
                        <p class="text-gray-600 text-sm">前往广州如意坊拍摄地方宣传短片，通过生动展现当地文化特色，提升了区域知名度和旅游吸引力。</p>
                    </div>
                    <div class="bg-white p-5 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h4 class="font-semibold mb-2">产品短视频广告</h4>
                        <p class="text-sm text-gray-500 mb-2">2019年9月</p>
                        <p class="text-gray-600 text-sm">为玩具《牛萌萌》拍摄3份短视频广告，投放于抖音、小红书、微信视频号等平台，取得良好市场反响。</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 专业技能 -->
    <section id="skills" class="py-16 bg-gray-50 section-fade">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold text-primary mb-4">专业技能</h2>
                <div class="w-20 h-1 bg-accent mx-auto mb-6"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">具备全面的项目管理与市场分析能力，熟练掌握多种专业工具，拥有出色的沟通协调与团队领导技能</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
                <div>
                    <h3 class="text-xl font-bold mb-6 flex items-center">
                        <i class="fa fa-cogs text-accent mr-3"></i>
                        核心能力
                    </h3>
                    
                    <div class="space-y-6">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium">项目管理与执行</span>
                                <span>90%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-value" style="width: 90%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium">市场分析与策略制定</span>
                                <span>85%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-value" style="width: 85%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium">团队协作与领导</span>
                                <span>88%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-value" style="width: 88%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium">沟通协调与谈判</span>
                                <span>92%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-value" style="width: 92%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium">数据分析与报告撰写</span>
                                <span>86%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-value" style="width: 86%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-6 flex items-center">
                        <i class="fa fa-desktop text-accent mr-3"></i>
                        专业工具与软件
                    </h3>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-white rounded-lg p-5 hover:shadow-md transition-shadow duration-300">
                            <div class="flex items-center mb-3">
                                <div class="w-10 h-10 bg-primary/10 rounded-full flex items-center justify-center mr-3">
                                    <i class="fa fa-file-text-o text-primary"></i>
                                </div>
                                <h4 class="font-semibold">办公软件</h4>
                            </div>
                            <p class="text-gray-600 text-sm">熟练使用Office办公软件、Visio、workflow，能高效完成文档处理与流程设计</p>
                        </div>
                        
                        <div class="bg-white rounded-lg p-5 hover:shadow-md transition-shadow duration-300">
                            <div class="flex items-center mb-3">
                                <div class="w-10 h-10 bg-primary/10 rounded-full flex items-center justify-center mr-3">
                                    <i class="fa fa-database text-primary"></i>
                                </div>
                                <h4 class="font-semibold">数据分析工具</h4>
                            </div>
                            <p class="text-gray-600 text-sm">熟练操作SPSS、AMOS、STATA，能进行复杂数据分析与建模</p>
                        </div>
                        
                        <div class="bg-white rounded-lg p-5 hover:shadow-md transition-shadow duration-300">
                            <div class="flex items-center mb-3">
                                <div class="w-10 h-10 bg-primary/10 rounded-full flex items-center justify-center mr-3">
                                    <i class="fa fa-code text-primary"></i>
                                </div>
                                <h4 class="font-semibold">编程语言</h4>
                            </div>
                            <p class="text-gray-600 text-sm">掌握Python编程语言，能进行数据处理与简单应用开发</p>
                        </div>
                        
                        <div class="bg-white rounded-lg p-5 hover:shadow-md transition-shadow duration-300">
                            <div class="flex items-center mb-3">
                                <div class="w-10 h-10 bg-primary/10 rounded-full flex items-center justify-center mr-3">
                                    <i class="fa fa-paint-brush text-primary"></i>
                                </div>
                                <h4 class="font-semibold">设计与AI工具</h4>
                            </div>
                            <p class="text-gray-600 text-sm">熟悉Adobe PS、AI、midjourney、chatgpt等设计与AI工具</p>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h3 class="text-xl font-bold mb-4 flex items-center">
                            <i class="fa fa-language text-accent mr-3"></i>
                            语言能力
                        </h3>
                        <div class="flex flex-wrap gap-3">
                            <div class="bg-white px-4 py-2 rounded-full flex items-center">
                                <span class="mr-2">中文</span>
                                <div class="flex">
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                </div>
                            </div>
                            <div class="bg-white px-4 py-2 rounded-full flex items-center">
                                <span class="mr-2">英语</span>
                                <div class="flex">
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star-o text-accent"></i>
                                    <i class="fa fa-star-o text-accent"></i>
                                </div>
                                <span class="ml-2 text-sm text-gray-500">(CET-4)</span>
                            </div>
                            <div class="bg-white px-4 py-2 rounded-full flex items-center">
                                <span class="mr-2">粤语</span>
                                <div class="flex">
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                    <i class="fa fa-star text-accent"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 教育背景 -->
    <section id="education" class="py-16 bg-white section-fade">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold text-primary mb-4">教育背景</h2>
                <div class="w-20 h-1 bg-accent mx-auto mb-6"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">系统的专业教育背景，为项目管理和销售工作奠定了坚实的理论基础</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-light rounded-lg shadow-sm overflow-hidden hover:shadow-md transition-shadow duration-300 transform hover:-translate-y-1">
                    <div class="bg-primary text-white p-6">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-bold">现代服务管理硕士</h3>
                            <span>2023-2026</span>
                        </div>
                        <p class="mt-2">广东财经大学</p>
                    </div>
                    <div class="p-6">
                        <p class="text-gray-600 mb-4">主修课程：微观经济学、宏观经济学、中级管理学、服务管理、市场营销、战略管理、数据分析与决策</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fa fa-award text-accent mr-2"></i>
                            <span>省级项目主持人、大学生创业大赛校赛银奖</span>
                        </div>
                    </div>
                </div>
                
                <div class="bg-light rounded-lg shadow-sm overflow-hidden hover:shadow-md transition-shadow duration-300 transform hover:-translate-y-1">
                    <div class="bg-primary text-white p-6">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-bold">旅游管理学士</h3>
                            <span>2018-2022</span>
                        </div>
                        <p class="mt-2">广州航海学院</p>
                    </div>
                    <div class="p-6">
                        <p class="text-gray-600 mb-4">主修课程：旅游管理学、市场营销学、酒店管理、会展管理、消费者行为学、商务沟通、项目策划与管理</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fa fa-award text-accent mr-2"></i>
                            <span>自媒体策划团队主持、校二、三等奖学金</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 bg-light rounded-lg shadow-sm p-6 md:p-8">
                <h3 class="text-xl font-bold mb-6 flex items-center">
                    <i class="fa fa-certificate text-accent mr-3"></i>
                    证书与荣誉
                </h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
                    <div class="border border-gray-100 rounded-lg p-4 hover:border-accent transition-colors duration-300 bg-white">
                        <h4 class="font-semibold mb-2">全国计算机等级二级</h4>
                        <p class="text-sm text-gray-500">计算机应用能力认证</p>
                        <p class="text-sm text-gray-600 mt-1">熟练掌握计算机操作与应用</p>
                    </div>
                    <div class="border border-gray-100 rounded-lg p-4 hover:border-accent transition-colors duration-300 bg-white">
                        <h4 class="font-semibold mb-2">全国英语CET4证书</h4>
                        <p class="text-sm text-gray-500">英语能力认证</p>
                        <p class="text-sm text-gray-600 mt-1">具备良好的英语听读写能力</p>
                    </div>
                    <div class="border border-gray-100 rounded-lg p-4 hover:border-accent transition-colors duration-300 bg-white">
                        <h4 class="font-semibold mb-2">全国大学生创新大赛</h4>
                        <p class="text-sm text-gray-500">校赛银奖</p>
                        <p class="text-sm text-gray-600 mt-1">以《壮瑶人家》项目获得</p>
                    </div>
                    <div class="border border-gray-100 rounded-lg p-4 hover:border-accent transition-colors duration-300 bg-white">
                        <h4 class="font-semibold mb-2">百千万突击队</h4>
                        <p class="text-sm text-gray-500">校重点项目立项</p>
                        <p class="text-sm text-gray-600 mt-1">参与乡村振兴相关项目</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 自我评价 -->
    <section class="py-16 bg-gray-50 section-fade">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto bg-primary/5 rounded-xl p-8 border border-primary/10">
                <div class="text-center mb-8">
                    <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold text-primary mb-4">自我评价</h2>
                    <div class="w-20 h-1 bg-accent mx-auto"></div>
                </div>
                
                <div class="prose prose-lg max-w-none text-gray-700">
                    <p class="mb-4">拥有5年以上项目管理、市场拓展和团队协作经验，具备出色的沟通协调能力、问题解决能力和数据分析能力。作为项目负责人，成功主导多个省级和校级项目，取得了显著成果。</p>
                    
                    <p class="mb-4">在销售与市场方面，具备扎实的理论基础和实践经验，成功参与贸易采购洽谈，推动销售增长，并通过有效的市场推广策略提升品牌影响力。熟悉消费电子和医疗器械等多个行业的市场动态和运营模式。</p>
                    
                    <p class="mb-4">具备较强的团队领导能力和组织协调能力，能够有效分配任务、激励团队成员，共同达成目标。工作积极主动，责任心强，具备良好的抗压能力和适应能力，能够接受高强度工作和出差安排。</p>
                    
                    <p>拥有扎实的学术背景和持续学习的能力，熟练掌握多种专业工具和软件，能够快速适应新的工作环境和挑战。期待能够加入贵公司，担任区域销售经理一职，为公司的销售目标达成贡献自己的力量。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 联系信息 -->
    <section id="contact" class="py-16 bg-gradient-to-br from-primary to-dark text-white section-fade">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold mb-4">联系我</h2>
                <div class="w-20 h-1 bg-accent mx-auto mb-6"></div>
                <p class="text-gray-300 max-w-2xl mx-auto">如果您认为我的经验和技能符合贵公司的要求，欢迎通过以下方式联系我，期待有机会进一步沟通</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-10 max-w-5xl mx-auto">
                <div>
                    <form class="bg-white/10 backdrop-blur-sm rounded-lg p-6 md:p-8">
                        <h3 class="text-xl font-bold mb-6">发送消息</h3>
                        
                        <div class="mb-4">
                            <label for="name" class="block mb-2 text-sm">姓名</label>
                            <input type="text" id="name" class="w-full px-4 py-3 bg-white/5 border border-white/20 rounded-md focus:outline-none focus:border-accent transition-colors" placeholder="您的姓名">
                        </div>
                        
                        <div class="mb-4">
                            <label for="email" class="block mb-2 text-sm">邮箱</label>
                            <input type="email" id="email" class="w-full px-4 py-3 bg-white/5 border border-white/20 rounded-md focus:outline-none focus:border-accent transition-colors" placeholder="您的邮箱">
                        </div>
                        
                        <div class="mb-6">
                            <label for="message" class="block mb-2 text-sm">消息</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-3 bg-white/5 border border-white/20 rounded-md focus:outline-none focus:border-accent transition-colors" placeholder="请输入您的消息..."></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-accent hover:bg-accent/90 text-white py-3 rounded-md font-medium transition-all duration-300 transform hover:scale-[1.02]">
                            发送消息
                        </button>
                    </form>
                </div>
                
                <div class="flex flex-col justify-center">
                    <div class="space-y-8">
                        <div class="flex items-start">
                            <div class="bg-white/10 p-4 rounded-full mr-4">
                                <i class="fa fa-phone text-accent text-xl"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-semibold mb-1">电话联系</h3>
                                <p class="text-gray-300">15360401565</p>
                                <p class="text-gray-400 text-sm mt-1">工作日 9:00-18:00</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-white/10 p-4 rounded-full mr-4">
                                <i class="fa fa-envelope text-accent text-xl"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-semibold mb-1">电子邮件</h3>
                                <p class="text-gray-300">870599702@qq.com</p>
                                <p class="text-gray-400 text-sm mt-1">通常24小时内回复</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-white/10 p-4 rounded-full mr-4">
                                <i class="fa fa-map-marker text-accent text-xl"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-semibold mb-1">所在地</h3>
                                <p class="text-gray-300">广东广州</p>
                                <p class="text-gray-400 text-sm mt-1">可接受全国范围内出差</p>
                            </div>
                        </div>
                        
                        <div class="pt-4">
                            <h3 class="text-xl font-semibold mb-4">社交媒体</h3>
                            <div class="flex space-x-4">
                                <a href="#" class="bg-white/10 hover:bg-accent w-10 h-10 rounded-full flex items-center justify-center transition-colors duration-300">
                                    <i class="fa fa-linkedin"></i>
                                </a>
                                <a href="#" class="bg-white/10 hover:bg-accent w-10 h-10 rounded-full flex items-center justify-center transition-colors duration-300">
                                    <i class="fa fa-weixin"></i>
                                </a>
                                <a href="#" class="bg-white/10 hover:bg-accent w-10 h-10 rounded-full flex items-center justify-center transition-colors duration-300">
                                    <i class="fa fa-weibo"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-dark text-white py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="flex items-center space-x-2 mb-2">
                        <i class="fa fa-briefcase text-accent text-xl"></i>
                        <span class="font-bold text-xl">吴泽鸿 - 项目管理专家</span>
                    </div>
                    <p class="text-gray-400 text-sm">应聘区域销售经理（中国区）职位</p>
                </div>
                
                <div class="text-gray-400 text-sm">
                    <p>© 2024 个人简历. 保留所有权利.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- 返回顶部按钮 -->
    <button id="backToTop" class="fixed bottom-8 right-8 bg-accent text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg transform transition-all duration-300 scale-0 hover:bg-accent/90">
        <i class="fa fa-arrow-up"></i>
    </button>

    <script>
        // 移动端菜单切换
        const menuToggle = document.getElementById('menuToggle');
        const mobileMenu = document.getElementById('mobileMenu');
        
        menuToggle.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // 导航栏滚动效果
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('py-2', 'bg-primary/95', 'backdrop-blur-sm');
                navbar.classList.remove('py-3');
            } else {
                navbar.classList.add('py-3');
                navbar.classList.remove('py-2', 'bg-primary/95', 'backdrop-blur-sm');
            }
        });
        
        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                // 关闭移动菜单（如果打开）
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // 返回顶部按钮
        const backToTopButton = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                backToTopButton.classList.replace('scale-0', 'scale-100');
            } else {
                backToTopButton.classList.replace('scale-100', 'scale-0');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // 滚动动画
        const observerOptions = {
            root: null,
            rootMargin: '0px',
            threshold: 0.1
        };
        
        const observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('section-visible');
                    observer.unobserve(entry.target);
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.section-fade').forEach(section => {
            observer.observe(section);
        });
        
        // 表单提交处理
        const contactForm = document.querySelector('#contact form');
        if (contactForm) {
            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();
                alert('感谢您的消息！我会尽快回复您。');
                contactForm.reset();
            });
        }
    </script>


</body></html>
