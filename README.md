# Filkilomhik.github.io
[index.html](https://github.com/user-attachments/files/23281807/index.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Filkilom - Социальные сети</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            color: white;
        }
        
        .container {
            max-width: 500px;
            width: 100%;
            background-color: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            overflow: hidden;
            padding: 30px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .profile {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: #000;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 5px solid #6a11cb;
            box-shadow: 0 0 20px rgba(106, 17, 203, 0.5);
        }
        
        .avatar-text {
            font-size: 22px; /* Уменьшенный размер шрифта */
            font-weight: 900; /* Очень жирный шрифт */
            color: white;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
            letter-spacing: 1px;
        }
        
        h1 {
            color: white;
            margin-bottom: 10px;
            font-size: 32px;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        
        .description {
            color: #b8b8b8;
            margin-bottom: 30px;
            line-height: 1.5;
            font-size: 16px;
        }
        
        .social-links {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            padding: 18px 25px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
            cursor: pointer;
        }
        
        .social-link:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
            background-color: rgba(255, 255, 255, 0.15);
        }
        
        .social-icon {
            width: 40px;
            height: 40px;
            margin-right: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
            font-size: 20px;
            color: white;
        }
        
        .telegram {
            background: linear-gradient(135deg, #0088cc, #00aced);
        }
        
        .youtube {
            background: linear-gradient(135deg, #ff0000, #cc0000);
        }
        
        .tiktok {
            background: linear-gradient(135deg, #000000, #333333);
        }
        
        .tiktok-backup {
            background: linear-gradient(135deg, #ff0050, #ff2d55);
        }
        
        .social-text {
            flex-grow: 1;
        }
        
        .social-arrow {
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .social-link:hover .social-arrow {
            opacity: 1;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #888;
            font-size: 14px;
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 26px;
            }
            
            .avatar {
                width: 120px;
                height: 120px;
            }
            
            .avatar-text {
                font-size: 18px; /* Уменьшенный размер для мобильных */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <div class="avatar">
                <div class="avatar-text">Filkilom</div>
            </div>
            <h1>Filkilom</h1>
            <p class="description">Создаю контент в разных социальных сетях. Подписывайтесь, чтобы быть в курсе всех новостей и обновлений!</p>
        </div>
        
        <div class="social-links">
            <a href="https://t.me/Filkilom_TG" class="social-link" target="_blank">
                <div class="social-icon telegram">
                    <i class="fab fa-telegram"></i>
                </div>
                <div class="social-text">Telegram</div>
                <div class="social-arrow">→</div>
            </a>
            
            <a href="https://www.youtube.com/@Filkilom" class="social-link" target="_blank">
                <div class="social-icon youtube">
                    <i class="fab fa-youtube"></i>
                </div>
                <div class="social-text">YouTube</div>
                <div class="social-arrow">→</div>
            </a>
            
            <a href="https://tiktok.com/@filkilom_yt" class="social-link" target="_blank">
                <div class="social-icon tiktok">
                    <i class="fab fa-tiktok"></i>
                </div>
                <div class="social-text">TikTok</div>
                <div class="social-arrow">→</div>
            </a>
            
            <a href="https://tiktok.com/@filkilom_zap" class="social-link" target="_blank">
                <div class="social-icon tiktok-backup">
                    <i class="fab fa-tiktok"></i>
                </div>
                <div class="social-text">TikTok (запасной)</div>
                <div class="social-arrow">→</div>
            </a>
        </div>
        
        <div class="footer">
            © 2023 Filkilom. Все права защищены.
        </div>
    </div>

    <script>
        // Добавляем небольшую анимацию при загрузке страницы
        document.addEventListener('DOMContentLoaded', function() {
            const links = document.querySelectorAll('.social-link');
            links.forEach((link, index) => {
                link.style.opacity = '0';
                link.style.transform = 'translateY(20px)';
                
                setTimeout(() => {
                    link.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                    link.style.opacity = '1';
                    link.style.transform = 'translateY(0)';
                }, 300 + (index * 150));
            });
        });
    </script>
</body>
</html>
