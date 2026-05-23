<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>智嵌科技 - AI与嵌入式融合创新</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0a0e17 0%, #1a1f2e 100%);
            color: #ffffff;
            line-height: 1.6;
        }

        /* 导航栏 */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.5rem 8%;
            background: rgba(10, 14, 23, 0.95);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #4cc9f0;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: #e0e0e0;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #4cc9f0;
        }

        /* 英雄区 */
        .hero {
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            background: radial-gradient(circle at center, rgba(76, 201, 240, 0.1) 0%, transparent 70%);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            background: linear-gradient(90deg, #4cc9f0, #4361ee);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .hero p {
            font-size: 1.3rem;
            color: #a0a0a0;
            max-width: 700px;
            margin-bottom: 2rem;
        }

        .cta-button {
            padding: 1rem 2.5rem;
            background: linear-gradient(90deg, #4cc9f0, #4361ee);
            border: none;
            border-radius: 50px;
            color: white;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(76, 201, 240, 0.3);
        }

        /* 产品服务区 */
        .services {
            padding: 5rem 8%;
        }

        .section-title {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 3rem;
            color: #ffffff;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: rgba(26, 31, 46, 0.8);
            border-radius: 16px;
            padding: 2rem;
            border: 1px solid rgba(76, 201, 240, 0.1);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-8px);
            border-color: #4cc9f0;
        }

        .service-card h3 {
            font-size: 1.4rem;
            margin-bottom: 1rem;
            color: #4cc9f0;
        }

        .service-card p {
            color: #b0b0b0;
        }

        /* 关于我们 */
        .about {
            padding: 5rem 8%;
            background: rgba(10, 14, 23, 0.5);
        }

        .about-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .about-content h2 {
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            color: #ffffff;
        }

        .about-content p {
            color: #b0b0b0;
            font-size: 1.1rem;
            line-height: 1.8;
        }

        /* 页脚 */
        footer {
            padding: 2rem;
            text-align: center;
            background: #0a0e17;
            color: #666;
        }

        /* 响应式适配 */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav>
        <div class="logo">SKP智嵌</div>
        <div class="nav-links">
            <a href="#home">首页</a>
            <a href="#services">服务</a>
            <a href="#about">关于我们</a>
            <a href="#contact">联系我们</a>
        </div>
    </nav>

    <!-- 英雄区 -->
    <section class="hero" id="home">
        <h1>AI 与嵌入式的融合创新</h1>
        <p>让智能算法走进硬件终端，用边缘计算赋能千行百业，打造低功耗、高可靠的下一代智能设备</p>
        <button class="cta-button">了解更多</button>
    </section>

    <!-- 产品服务区 -->
    <section class="services" id="services">
        <h2 class="section-title">核心服务</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>AI 边缘部署方案</h3>
                <p>为嵌入式设备提供轻量化AI模型移植、优化与部署服务，让算法在低功耗硬件上高效运行，降低云端依赖。</p>
            </div>
            <div class="service-card">
                <h3>智能硬件定制开发</h3>
                <p>基于STM32、ESP32等平台，提供从需求分析、硬件设计到固件开发的一站式嵌入式系统解决方案。</p>
            </div>
            <div class="service-card">
                <h3>行业解决方案落地</h3>
                <p>针对工业控制、智能家居、物联网等场景，提供AI+嵌入式的端到端解决方案，助力客户实现智能化升级。</p>
            </div>
        </div>
    </section>

    <!-- 关于我们 -->
    <section class="about" id="about">
        <div class="about-content">
            <h2>关于智嵌科技</h2>
            <p>我们是一支专注于AI与嵌入式融合领域的技术团队，深耕边缘计算与智能硬件开发多年。我们坚信，真正的智能不应局限于云端，而是要走进每一台设备、每一个场景。凭借对算法优化、低功耗设计和实时系统的深刻理解，我们帮助客户将AI能力高效落地到终端设备，让智能触手可及。</p>
        </div>
    </section>

    <!-- 页脚 -->
    <footer>
        <p>© 2024 智嵌科技 | AI与嵌入式融合创新服务商</p>
    </footer>

    <script>
        // 平滑滚动效果
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // 按钮点击交互
        document.querySelector('.cta-button').addEventListener('click', () => {
            document.querySelector('#services').scrollIntoView({
                behavior: 'smooth'
            });
        });

        // 滚动时导航栏背景变化
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 50) {
                nav.style.background = 'rgba(10, 14, 23, 0.98)';
            } else {
                nav.style.background = 'rgba(10, 14, 23, 0.95)';
            }
        });
    </script>
</body>
</html># my-website
