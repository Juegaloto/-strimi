<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Store Max - Servicios Digitales Premium</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --cuba-blue: #002A8F;
            --cuba-blue-light: #1a4cb3;
            --cuba-white: #FFFFFF;
            --cuba-red: #CF142B;
            --cuba-red-light: #e02a40;
            --accent: #FFD700; /* Oro como acento */
            --light: #f8f9fa;
            --dark: #212529;
            --dark-bg: #12141d;
            --success: #2ecc71;
            --warning: #f39c12;
            --danger: #e74c3c;
            --gradient: linear-gradient(135deg, var(--cuba-blue), var(--cuba-red));
            --card-bg: rgba(255, 255, 255, 0.05);
            --text-muted: rgba(255, 255, 255, 0.7);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: var(--dark-bg);
            color: var(--light);
            line-height: 1.7;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        /* Banner de Anuncios Moderno */
        .admin-banner {
            background: linear-gradient(90deg, var(--cuba-blue) 0%, var(--cuba-blue-light) 50%, var(--cuba-blue) 100%);
            color: white;
            padding: 12px 0;
            position: relative;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            z-index: 999;
            display: none;
            border-bottom: 3px solid var(--cuba-red);
        }

        .admin-banner-content {
            position: relative;
            padding: 0 40px 0 20px;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .admin-banner h4 {
            font-size: 1.1rem;
            margin-bottom: 0;
            font-weight: 700;
            color: var(--accent);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .admin-banner h4:before {
            content: '';
            display: inline-block;
            width: 20px;
            height: 20px;
            background-color: var(--cuba-red);
            mask: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9'%3E%3C/path%3E%3Cpath d='M13.73 21a2 2 0 0 1-3.46 0'%3E%3C/path%3E%3C/svg%3E");
            -webkit-mask: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9'%3E%3C/path%3E%3Cpath d='M13.73 21a2 2 0 0 1-3.46 0'%3E%3C/path%3E%3C/svg%3E");
            mask-repeat: no-repeat;
            background-size: contain;
        }

        .admin-banner p {
            font-size: 0.9rem;
            margin-bottom: 0;
            opacity: 0.9;
            line-height: 1.4;
        }

        .timestamp {
            font-size: 0.75rem;
            opacity: 0.7;
            display: flex;
            align-items: center;
            gap: 5px;
            margin-top: 5px;
        }

        .timestamp:before {
            content: '\f017';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            font-size: 0.7rem;
        }

        .close-banner {
            position: absolute;
            top: 50%;
            right: 15px;
            transform: translateY(-50%);
            font-size: 1.3rem;
            cursor: pointer;
            transition: all 0.3s ease;
            padding: 5px;
            line-height: 1;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            width: 25px;
            height: 25px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .close-banner:hover {
            background: var(--cuba-red);
            transform: translateY(-50%) scale(1.1);
        }

        .btn-banner {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 6px 12px;
            background: var(--cuba-red);
            border-radius: 20px;
            color: white;
            font-size: 0.8rem;
            margin-top: 8px;
            transition: all 0.3s ease;
            text-decoration: none;
            font-weight: 500;
            width: fit-content;
        }

        .btn-banner:hover {
            background: var(--cuba-red-light);
            transform: translateY(-2px);
            box-shadow: 0 3px 10px rgba(207, 20, 43, 0.4);
        }

        /* Estilos para el indicador de anuncios */
        .nav-notification {
            position: absolute;
            top: -5px;
            right: -5px;
            width: 18px;
            height: 18px;
            background-color: var(--cuba-red);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.7rem;
            font-weight: bold;
            animation: pulse 1.5s infinite;
            border: 2px solid var(--dark-bg);
        }

        /* Modal de anuncios */
        .announcements-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(5px);
        }

        .announcements-content {
            background: linear-gradient(to bottom, rgba(33, 37, 41, 0.95), rgba(18, 20, 29, 0.98));
            padding: 30px;
            border-radius: 15px;
            width: 90%;
            max-width: 600px;
            max-height: 80vh;
            overflow-y: auto;
            border: 1px solid rgba(76, 201, 240, 0.3);
            position: relative;
            animation: modalFadeIn 0.4s ease-out;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
        }

        .announcements-content::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
        }

        .announcements-title {
            text-align: center;
            margin-bottom: 25px;
            color: var(--accent);
            font-size: 1.6rem;
            font-weight: 700;
            position: relative;
            padding-bottom: 15px;
        }

        .announcements-title:after {
            content: '';
            position: absolute;
            width: 60px;
            height: 3px;
            background: var(--gradient);
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        .announcement-item {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            position: relative;
        }

        .announcement-item.unread {
            border-left: 4px solid var(--cuba-red);
        }

        .announcement-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: var(--accent);
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .announcement-title:before {
            content: '';
            display: inline-block;
            width: 8px;
            height: 8px;
            background-color: var(--cuba-red);
            border-radius: 50%;
        }

        .announcement-message {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .announcement-timestamp {
            font-size: 0.8rem;
            opacity: 0.7;
            text-align: right;
            display: flex;
            align-items: center;
            justify-content: flex-end;
            gap: 5px;
        }

        .announcement-timestamp:before {
            content: '\f017';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            font-size: 0.7rem;
        }

        .announcement-link {
            display: inline-flex;
            align-items: center;
            gap: 5px;
            margin-top: 10px;
            color: var(--cuba-red);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }

        .announcement-link:hover {
            color: var(--cuba-red-light);
            transform: translateX(5px);
        }

        .close-announcements {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 1.8rem;
            color: var(--text-muted);
            cursor: pointer;
            transition: all 0.3s ease;
            z-index: 1;
        }

        .close-announcements:hover {
            color: var(--danger);
            transform: rotate(90deg);
        }

        .no-announcements {
            text-align: center;
            padding: 30px;
            color: var(--text-muted);
            font-size: 1.1rem;
        }

        /* Animaciones */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes modalFadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(207, 20, 43, 0.7); }
            70% { box-shadow: 0 0 0 15px rgba(207, 20, 43, 0); }
            100% { box-shadow: 0 0 0 0 rgba(207, 20, 43, 0); }
        }

        .container {
            width: 100%;
            padding: 0 20px;
            margin: 0 auto;
            max-width: 1200px;
        }

        /* Header */
        header {
            background: rgba(18, 20, 29, 0.98);
            backdrop-filter: blur(10px);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.2);
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 800;
            font-size: 1.4rem;
            color: white;
            text-decoration: none;
        }

        .logo i {
            color: var(--accent);
            font-size: 1.6rem;
            transition: transform 0.3s ease;
        }

        .logo:hover i {
            transform: rotate(-15deg);
        }

        .logo span {
            background: linear-gradient(45deg, var(--accent), var(--cuba-red));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .menu-toggle {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            width: 30px;
            height: 21px;
            cursor: pointer;
            z-index: 1001;
            transition: all 0.3s ease;
        }

        .menu-toggle span {
            height: 3px;
            width: 100%;
            background-color: var(--light);
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .menu-toggle.active span:nth-child(1) {
            transform: translateY(9px) rotate(45deg);
        }

        .menu-toggle.active span:nth-child(2) {
            opacity: 0;
        }

        .menu-toggle.active span:nth-child(3) {
            transform: translateY(-9px) rotate(-45deg);
        }

        .nav-links {
            position: fixed;
            top: 0;
            right: -100%;
            width: 80%;
            max-width: 350px;
            height: 100vh;
            background: rgba(33, 37, 41, 0.98);
            backdrop-filter: blur(15px);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 25px;
            transition: right 0.5s cubic-bezier(0.77, 0.2, 0.05, 1);
            z-index: 1000;
            padding-top: 80px;
        }

        .nav-links.active {
            right: 0;
        }

        .nav-links a {
            color: var(--light);
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: 500;
            transition: all 0.4s ease;
            padding: 12px 25px;
            border-radius: 30px;
            background: rgba(207, 20, 43, 0.1);
            width: 80%;
            text-align: center;
            border: 1px solid rgba(207, 20, 43, 0.2);
            position: relative;
        }

        .nav-links a:hover {
            background: rgba(207, 20, 43, 0.3);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(207, 20, 43, 0.2);
        }

        .close-btn {
            position: absolute;
            top: 25px;
            right: 25px;
            color: white;
            font-size: 1.8rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .close-btn:hover {
            color: var(--cuba-red);
            transform: rotate(90deg);
        }

        /* Banner Informativo */
        .info-banner {
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            padding: 15px;
            text-align: center;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0, 42, 143, 0.3);
            animation: float 6s ease-in-out infinite;
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
            overflow: hidden;
        }

        .info-banner::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            z-index: 0;
        }

        .info-banner p {
            font-size: 1rem;
            margin-bottom: 0;
            color: white;
            font-weight: 500;
            position: relative;
            z-index: 1;
        }

        .info-banner i {
            margin-right: 8px;
            color: var(--accent);
        }

        /* Hero Section */
        .hero {
            padding: 80px 0 50px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle at 30% 50%, rgba(0, 42, 143, 0.15) 0%, rgba(18, 20, 29, 0) 70%);
            z-index: -1;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #ffffff, var(--accent));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            line-height: 1.3;
            font-weight: 800;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        .hero p {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-bottom: 30px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            color: var(--text-muted);
        }

        .hero-btns {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 25px;
            max-width: 350px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn {
            padding: 14px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            display: inline-block;
            transition: all 0.3s ease;
            text-align: center;
            font-size: 1rem;
            position: relative;
            overflow: hidden;
            z-index: 1;
            border: none;
            cursor: pointer;
            letter-spacing: 0.5px;
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            color: white;
            box-shadow: 0 5px 20px rgba(0, 42, 143, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 42, 143, 0.5);
        }

        .btn-primary:active {
            transform: translateY(1px);
        }

        .btn-secondary {
            background: transparent;
            color: var(--light);
            border: 2px solid var(--cuba-red);
        }

        .btn-secondary:hover {
            background: rgba(207, 20, 43, 0.1);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(207, 20, 43, 0.2);
        }

        .btn i {
            margin-right: 8px;
        }

        /* Services Section */
        .section-title {
            text-align: center;
            margin: 60px 0 40px;
            position: relative;
        }

        .section-title h2 {
            font-size: 2.2rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #ffffff, var(--accent));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 800;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        .section-title p {
            font-size: 1.1rem;
            opacity: 0.8;
            max-width: 700px;
            margin: 0 auto;
            color: var(--text-muted);
        }

        .section-title:after {
            content: '';
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
            position: absolute;
            bottom: -20px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
            margin-bottom: 60px;
        }

        .service-card {
            background: var(--card-bg);
            border-radius: 15px;
            overflow: hidden;
            transition: all 0.4s ease;
            position: relative;
            border: 1px solid rgba(255, 255, 255, 0.08);
            animation: fadeIn 0.6s ease-out;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.25);
            border-color: rgba(207, 20, 43, 0.3);
        }

        .service-header {
            padding: 20px;
            text-align: center;
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            position: relative;
            overflow: hidden;
        }

        .service-header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            z-index: 0;
        }

        .service-header i {
            font-size: 2.5rem;
            margin-bottom: 15px;
            display: block;
            color: white;
            position: relative;
            z-index: 1;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .service-header h3 {
            font-size: 1.5rem;
            font-weight: 700;
            color: white;
            position: relative;
            z-index: 1;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .service-body {
            padding: 25px;
        }

        .service-features {
            list-style: none;
            margin: 20px 0;
        }

        .service-features li {
            padding: 10px 0;
            position: relative;
            padding-left: 35px;
            font-size: 0.95rem;
            color: var(--text-muted);
        }

        .service-features li:before {
            content: '\f00c';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            color: var(--success);
            font-size: 1.1rem;
        }

        .price {
            font-size: 1.8rem;
            font-weight: 800;
            text-align: center;
            margin: 25px 0;
            color: var(--accent);
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .price span {
            font-size: 1rem;
            font-weight: normal;
            opacity: 0.8;
            color: var(--text-muted);
        }

        .service-footer {
            padding: 0 20px 25px;
            text-align: center;
        }

        .btn-buy {
            width: 100%;
            padding: 12px;
            font-size: 1rem;
            font-weight: 600;
            border-radius: 8px;
            transition: all 0.3s ease;
            background: linear-gradient(135deg, var(--cuba-red), var(--cuba-red-light));
        }

        .btn-buy:hover {
            animation: pulse 1.5s infinite;
        }

        /* Reseller Section */
        .reseller {
            padding: 60px 0;
            background: linear-gradient(135deg, rgba(33, 37, 41, 0.8), rgba(18, 20, 29, 0.9));
            border-radius: 15px;
            margin: 60px 0;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .reseller::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(207, 20, 43, 0.1) 0%, rgba(18, 20, 29, 0) 70%);
            z-index: -1;
        }

        .reseller-content {
            padding: 30px;
        }

        .reseller-content h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 25px;
            color: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            font-weight: 700;
        }

        .reseller-content p {
            text-align: center;
            max-width: 700px;
            margin: 0 auto 30px;
            color: var(--text-muted);
            font-size: 1.1rem;
        }

        .steps {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
            margin: 40px 0;
        }

        .step-card {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            padding: 25px;
            text-align: center;
            transition: all 0.4s ease;
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
            position: relative;
            overflow: hidden;
        }

        .step-card:hover {
            background: rgba(0, 42, 143, 0.1);
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
            border-color: rgba(207, 20, 43, 0.3);
        }

        .step-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
        }

        .step-number {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 1.4rem;
            font-weight: 700;
            color: white;
            box-shadow: 0 5px 15px rgba(0, 42, 143, 0.4);
        }

        .step-card h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: var(--accent);
            font-weight: 600;
        }

        .step-card p {
            color: var(--text-muted);
            font-size: 0.95rem;
            margin-bottom: 0;
        }

        .warning-box {
            background: rgba(243, 156, 18, 0.1);
            border: 1px solid var(--warning);
            border-radius: 12px;
            padding: 20px;
            margin: 30px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .warning-box::before {
            content: '\f071';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            position: absolute;
            top: -20px;
            left: -20px;
            font-size: 5rem;
            color: rgba(243, 156, 18, 0.1);
            z-index: 0;
        }

        .warning-box p {
            font-size: 1rem;
            color: var(--warning);
            font-weight: 600;
            position: relative;
            z-index: 1;
        }

        .warning-box i {
            margin-right: 10px;
        }

        .reseller-contact {
            text-align: center;
            margin-top: 30px;
        }

        .reseller-contact h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            color: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        /* Footer */
        footer {
            padding: 60px 0 30px;
            background: linear-gradient(135deg, rgba(33, 37, 41, 0.9), rgba(18, 20, 29, 1));
            position: relative;
            margin-top: 60px;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
        }

        .footer-content {
            display: grid;
            grid-template-columns: 1fr;
            gap: 40px;
        }

        .footer-logo {
            font-weight: 800;
            font-size: 2rem;
            background: linear-gradient(45deg, var(--accent), var(--cuba-red));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 20px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .footer-logo i {
            font-size: 1.8rem;
        }

        .footer-info p {
            text-align: center;
            font-size: 1rem;
            margin-bottom: 20px;
            color: var(--text-muted);
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.08);
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            font-size: 1.3rem;
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .social-links a:hover {
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 42, 143, 0.4);
            color: white;
        }

        .footer-title {
            font-size: 1.4rem;
            margin-bottom: 20px;
            color: var(--accent);
            position: relative;
            padding-bottom: 15px;
            text-align: center;
            font-weight: 600;
        }

        .footer-title:after {
            content: '';
            position: absolute;
            width: 60px;
            height: 3px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        .footer-links {
            list-style: none;
            text-align: center;
        }

        .footer-links li {
            margin-bottom: 12px;
        }

        .footer-links a {
            color: var(--text-muted);
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-block;
            padding: 5px 0;
            font-size: 1rem;
        }

        .footer-links a:hover {
            color: var(--accent);
            transform: translateX(5px);
        }

        .footer-links i {
            margin-right: 8px;
            width: 20px;
            text-align: center;
        }

        .copyright {
            text-align: center;
            padding-top: 40px;
            margin-top: 40px;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        /* Modal de Compra */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background: linear-gradient(to bottom, rgba(33, 37, 41, 0.95), rgba(18, 20, 29, 0.98));
            padding: 30px;
            border-radius: 15px;
            width: 90%;
            max-width: 500px;
            border: 1px solid rgba(76, 201, 240, 0.3);
            position: relative;
            animation: modalFadeIn 0.4s ease-out;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
            overflow: hidden;
        }

        .modal-content::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
        }

        .close-modal {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 1.8rem;
            color: var(--text-muted);
            cursor: pointer;
            transition: all 0.3s ease;
            z-index: 1;
        }

        .close-modal:hover {
            color: var(--danger);
            transform: rotate(90deg);
        }

        .modal-title {
            text-align: center;
            margin-bottom: 25px;
            color: var(--accent);
            font-size: 1.6rem;
            font-weight: 700;
            position: relative;
            padding-bottom: 15px;
        }

        .modal-title:after {
            content: '';
            position: absolute;
            width: 60px;
            height: 3px;
            background: linear-gradient(90deg, var(--cuba-blue), var(--cuba-red));
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        .modal-message {
            background: rgba(0, 0, 0, 0.3);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 25px;
            font-size: 1rem;
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .modal-message p {
            margin-bottom: 10px;
        }

        .modal-message p:last-child {
            margin-bottom: 0;
        }

        .modal-actions {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        /* Scrollbar */
        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-track {
            background: var(--dark-bg);
        }

        ::-webkit-scrollbar-thumb {
            background: linear-gradient(var(--cuba-blue), var(--cuba-red));
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--cuba-red);
        }

        /* Back to Top Button */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--cuba-blue), var(--cuba-blue-light));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.3rem;
            cursor: pointer;
            transition: all 0.3s ease;
            opacity: 0;
            visibility: hidden;
            z-index: 999;
            box-shadow: 0 5px 20px rgba(0, 42, 143, 0.4);
            border: none;
        }

        .back-to-top.visible {
            opacity: 1;
            visibility: visible;
        }

        .back-to-top:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 42, 143, 0.5);
        }

        /* Media Queries */
        @media (min-width: 576px) {
            .container {
                padding: 0 25px;
            }
            
            .hero h1 {
                font-size: 2.8rem;
            }
            
            .hero-btns {
                flex-direction: row;
                max-width: none;
                justify-content: center;
            }
            
            .btn {
                padding: 14px 30px;
            }
            
            .info-banner p {
                font-size: 1.1rem;
            }
        }

        @media (min-width: 768px) {
            .container {
                max-width: 720px;
            }
            
            .services-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 30px;
            }
            
            .steps {
                grid-template-columns: repeat(2, 1fr);
                gap: 30px;
            }

            .hero h1 {
                font-size: 3.2rem;
            }
            
            .section-title h2 {
                font-size: 2.5rem;
            }
            
            .nav-links {
                position: static;
                width: auto;
                height: auto;
                background: transparent;
                backdrop-filter: none;
                flex-direction: row;
                padding-top: 0;
                gap: 15px;
            }
            
            .nav-links a {
                width: auto;
                padding: 8px 15px;
                font-size: 0.95rem;
                background: transparent;
            }
            
            .nav-links a:hover {
                background: rgba(207, 20, 43, 0.1);
            }
            
            .menu-toggle, .close-btn {
                display: none;
            }
            
            .footer-content {
                grid-template-columns: repeat(3, 1fr);
                text-align: left;
            }
            
            .footer-logo, .footer-info p, .footer-title, .footer-links {
                text-align: left;
                justify-content: flex-start;
            }
            
            .social-links {
                justify-content: flex-start;
            }
            
            .footer-title:after {
                left: 0;
                transform: none;
            }
            
            /* Admin Banner Responsive */
            .admin-banner h4 {
                font-size: 1.3rem;
            }
            
            .admin-banner p {
                font-size: 1rem;
            }
        }

        @media (min-width: 992px) {
            .container {
                max-width: 960px;
            }
            
            .services-grid {
                grid-template-columns: repeat(3, 1fr);
            }
            
            .steps {
                grid-template-columns: repeat(4, 1fr);
            }
            
            .hero h1 {
                font-size: 3.5rem;
            }
            
            .section-title h2 {
                font-size: 2.8rem;
            }
            
            .nav-links {
                gap: 20px;
            }
            
            .nav-links a {
                padding: 10px 20px;
                font-size: 1rem;
            }
        }

        @media (min-width: 1200px) {
            .container {
                max-width: 1140px;
            }
            
            .hero h1 {
                font-size: 4rem;
            }
        }
    </style>
</head>
<body>
    <!-- Banner de Anuncios Administrables -->
    <div class="admin-banner" id="adminBanner">
        <div class="container">
            <div class="admin-banner-content">
                <span class="close-banner" id="closeBanner">&times;</span>
                <h4 id="bannerTitle">¡Nueva Actualización!</h4>
                <p id="bannerMessage">Ahora ofrecemos servicios de VPN Cuba con IP local para acceder a bancos y ENZONA desde el exterior. ¡Pregunta por este y otros servicios!</p>
                <p id="bannerTimestamp" class="timestamp"></p>
                <a href="https://t.me/DaymelTech" id="bannerLink" class="btn btn-banner">
                    <i class="fas fa-external-link-alt"></i> Contactar
                </a>
            </div>
        </div>
    </div>

    <!-- Header -->
    <header>
        <div class="container">
            <div class="navbar">
                <a href="#" class="logo">
                    <i class="fas fa-store-alt"></i> <span>Digital Store Max</span>
                </a>
                <div class="menu-toggle" id="mobile-menu">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="nav-links" id="nav-links">
                    <div class="close-btn" id="close-menu">
                        <i class="fas fa-times"></i>
                    </div>
                    <a href="#inicio">Inicio</a>
                    <a href="#servicios">Servicios</a>
                    <a href="#reventa">Reventa</a>
                    <a href="#contacto">Contacto</a>
                    <a href="#" id="announcements-link">
                        <i class="fas fa-bullhorn"></i> Anuncios
                        <span class="nav-notification" id="announcements-badge" style="display: none;"></span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="inicio">
        <div class="container">
            <h1 class="animate">Servicios Digitales Premium</h1>
            <p class="animate">📡 Somos una tienda en línea en crecimiento, ofrecemos diversos servicios digitales para Cuba y el mundo con la mejor calidad y soporte.</p>
            
            <!-- Banner Informativo -->
            <div class="info-banner animate">
                <p><i class="fas fa-info-circle"></i> Todos nuestros servicios incluyen garantía y soporte 24/7. Métodos de pago: Transfermovil, Enzona y MLC.</p>
            </div>
            
            <div class="hero-btns">
                <a href="https://t.me/tech_digital_store" class="btn btn-primary animate">
                    <i class="fab fa-telegram"></i> Únete a nuestro canal
                </a>
                <a href="#servicios" class="btn btn-secondary animate">
                    <i class="fas fa-tv"></i> Ver Servicios
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="servicios">
        <div class="container">
            <div class="section-title">
                <h2>Nuestros Servicios Premium</h2>
                <p>Ofrecemos las mejores plataformas de streaming y herramientas digitales al mejor precio del mercado</p>
            </div>
            
            <div class="services-grid">
                <!-- Tarjeta de Servicio 1 - Disney+ -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-crown"></i>
                        <h3>Disney+ Premium</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Películas y series de Disney, Pixar, Marvel</li>
                            <li>Contenido exclusivo y original</li>
                            <li>Perfecto para toda la familia</li>
                            <li>Sin anuncios molestos</li>
                        </ul>
                        <div class="price">1000 CUP <span>Plan Estándar</span></div>
                        <div class="price">1300 CUP <span>Plan Premium</span></div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Disney+ Premium" data-price="1000-1300 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 2 - HBO Max -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fab fa-hbo"></i>
                        <h3>HBO Max</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Series y películas aclamadas</li>
                            <li>Contenido exclusivo de HBO</li>
                            <li>Ideal para amantes de historias</li>
                            <li>Sin anuncios</li>
                        </ul>
                        <div class="price">850 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="HBO Max" data-price="850 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 3 - Prime Video -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fab fa-amazon"></i>
                        <h3>Prime Video</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Amplia selección de películas y series</li>
                            <li>Contenido exclusivo Amazon Originals</li>
                            <li>Descargas para ver sin conexión</li>
                            <li>Ideal para toda la familia</li>
                        </ul>
                        <div class="price">900 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Prime Video" data-price="900 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 4 - Vix+ -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-play-circle"></i>
                        <h3>Vix+ Premium</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Amplia variedad de series y películas</li>
                            <li>Contenido exclusivo y original</li>
                            <li>Sin anuncios molestos</li>
                            <li>Disfrute en familia</li>
                        </ul>
                        <div class="price">900 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Vix+ Premium" data-price="900 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 5 - Paramount+ -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-film"></i>
                        <h3>Paramount+</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Vasta biblioteca de películas y series</li>
                            <li>Contenido exclusivo de Paramount</li>
                            <li>Ideal para amantes del cine</li>
                            <li>Sin anuncios</li>
                        </ul>
                        <div class="price">850 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Paramount+" data-price="850 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 6 - Spotify -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fab fa-spotify"></i>
                        <h3>Spotify Premium</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Millones de canciones y podcasts</li>
                            <li>Descargas para escuchar sin conexión</li>
                            <li>Reproducción sin anuncios</li>
                            <li>Listas personalizadas</li>
                        </ul>
                        <div class="price">1200 CUP/mes</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Spotify Premium" data-price="1200 CUP/mes">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 7 - Crunchyroll -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-dragon"></i>
                        <h3>Crunchyroll</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Amplia variedad de animes</li>
                            <li>Estrenos simulcast</li>
                            <li>Contenido exclusivo</li>
                            <li>Para amantes del anime</li>
                        </ul>
                        <div class="price">950 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Crunchyroll" data-price="950 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 8 - Apple TV+ -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fab fa-apple"></i>
                        <h3>Apple TV+</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Series originales y películas exclusivas</li>
                            <li>Nuevo contenido regularmente</li>
                            <li>Compatible con múltiples dispositivos</li>
                            <li>Requiere VPN para acceso</li>
                        </ul>
                        <div class="price">850 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Apple TV+" data-price="850 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 9 - Canva Pro -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-paint-brush"></i>
                        <h3>Canva Pro</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Miles de plantillas y elementos</li>
                            <li>Herramientas avanzadas de diseño</li>
                            <li>Trabajo en equipo</li>
                            <li>Almacenamiento en la nube</li>
                        </ul>
                        <div class="price">850 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Canva Pro" data-price="850 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 10 - Surfshark VPN -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-shield-alt"></i>
                        <h3>Surfshark VPN</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Navegación segura y privada</li>
                            <li>Acceso a contenido restringido</li>
                            <li>Protección contra malware</li>
                            <li>Para cualquier dispositivo</li>
                        </ul>
                        <div class="price">700 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Surfshark VPN" data-price="700 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 11 - PayPal Argentina -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fab fa-paypal"></i>
                        <h3>PayPal Argentina</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Cuenta verificada con tus datos</li>
                            <li>Para enviar y recibir dólares</li>
                            <li>Pagos en tiendas online</li>
                            <li>Requiere VPN para uso</li>
                        </ul>
                        <div class="price">2500 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="PayPal Argentina" data-price="2500 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 12 - Conexión Ilimitada -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-wifi"></i>
                        <h3>Conexión Ilimitada</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Internet ilimitado para Nauta Hogar</li>
                            <li>15 días por 16 MLC</li>
                            <li>30 días por 22 MLC</li>
                            <li>Conexión estable y rápida</li>
                        </ul>
                        <div class="price">16-22 MLC</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Conexión Ilimitada" data-price="16-22 MLC">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 13 - Números Virtuales -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-mobile-alt"></i>
                        <h3>Números Virtuales</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>Verifica cuentas en WhatsApp, Telegram</li>
                            <li>Sin comprometer tu número personal</li>
                            <li>Funciona desde cualquier país</li>
                            <li>Seguridad garantizada</li>
                        </ul>
                        <div class="price">1300 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Números Virtuales" data-price="1300 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 14 - VPN Cuba -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-globe-americas"></i>
                        <h3>VPN Cuba</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>IP de Cuba para Nauta/Etecsa</li>
                            <li>Acceso a ENZONA y bancos cubanos</li>
                            <li>APK Viajando y páginas ETECSA</li>
                            <li>25 GB de tráfico incluido</li>
                        </ul>
                        <div class="price">850 CUP/30 días</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="VPN Cuba" data-price="850 CUP/30 días">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
                
                <!-- Tarjeta de Servicio 15 - Estrellas Telegram -->
                <div class="service-card animate">
                    <div class="service-header">
                        <i class="fas fa-star"></i>
                        <h3>Estrellas Telegram</h3>
                    </div>
                    <div class="service-body">
                        <ul class="service-features">
                            <li>¡Brilla en Telegram!</li>
                            <li>Cada ⭐ vale 7 CUP</li>
                            <li>Mínimo compra 50 ⭐</li>
                            <li>Múltiples métodos de pago</li>
                        </ul>
                        <div class="price">Desde 350 CUP</div>
                    </div>
                    <div class="service-footer">
                        <button class="btn btn-primary btn-buy" data-service="Estrellas Telegram" data-price="Desde 350 CUP">
                            <i class="fas fa-shopping-cart"></i> Comprar Ahora
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Reseller Section -->
    <section class="reseller" id="reventa">
        <div class="container">
            <div class="reseller-content">
                <h2 class="animate"><i class="fas fa-money-bill-wave"></i> Programa de Reventa</h2>
                <p class="animate">🌟 ¿Te gustaría generar ingresos con nuestros servicios? 🌟</p>
                
                <div class="steps">
                    <div class="step-card animate">
                        <div class="step-number">1</div>
                        <h3>Crea tus posts</h3>
                        <p>Publica en redes sociales</p>
                    </div>
                    
                    <div class="step-card animate">
                        <div class="step-number">2</div>
                        <h3>Añade ganancia</h3>
                        <p>Establece tu propio precio</p>
                    </div>
                    
                    <div class="step-card animate">
                        <div class="step-number">3</div>
                        <h3>Atiende clientes</h3>
                        <p>Recolecta información</p>
                    </div>
                    
                    <div class="step-card animate">
                        <div class="step-number">4</div>
                        <h3>Gana dinero</h3>
                        <p>Recibe tu comisión</p>
                    </div>
                </div>
                
                <div class="warning-box animate">
                    <p><i class="fas fa-exclamation-triangle"></i> NO SE HACEN DEVOLUCIONES EN CUANTO SE LE ACTIVA UN SERVICIO, A MENOS QUE DE POR NUESTRA PARTE, NO PODAMOS GARANTIZARLO</p>
                </div>
                
                <div class="reseller-contact animate">
                    <h3><i class="fas fa-headset"></i> ¿Dudas? Contacta al CEO</h3>
                    <a href="https://t.me/DaymelTech" class="btn btn-primary" style="margin-top: 15px;">
                        <i class="fab fa-telegram"></i> @DaymelTech
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contacto">
        <div class="container">
            <div class="footer-content">
                <div class="footer-info">
                    <div class="footer-logo">
                        <i class="fas fa-store-alt"></i> Digital Store Max
                    </div>
                    <p>📡 Servicios digitales premium para Cuba y el mundo con la mejor calidad y soporte técnico.</p>
                    <div class="social-links">
                        <a href="https://t.me/tech_digital_store"><i class="fab fa-telegram"></i></a>
                        <a href="#"><i class="fab fa-whatsapp"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                
                <div class="footer-links-section">
                    <h3 class="footer-title">Enlaces Rápidos</h3>
                    <ul class="footer-links">
                        <li><a href="#inicio"><i class="fas fa-home"></i> Inicio</a></li>
                        <li><a href="#servicios"><i class="fas fa-tv"></i> Servicios</a></li>
                        <li><a href="#reventa"><i class="fas fa-money-bill-wave"></i> Reventa</a></li>
                        <li><a href="#contacto"><i class="fas fa-envelope"></i> Contacto</a></li>
                    </ul>
                </div>
                
                <div class="footer-contact">
                    <h3 class="footer-title">Contacto</h3>
                    <ul class="footer-links">
                        <li><a href="https://t.me/tech_digital_store"><i class="fab fa-telegram"></i> Canal Oficial</a></li>
                        <li><a href="https://t.me/DaymelTech"><i class="fab fa-telegram"></i> Soporte Técnico</a></li>
                        <li><a href="#"><i class="fas fa-envelope"></i> Email</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>© 2024 Digital Store Max. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button class="back-to-top" id="backToTop">
        <i class="fas fa-arrow-up"></i>
    </button>

    <!-- Modal de Compra -->
    <div class="modal" id="purchaseModal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h3 class="modal-title">Confirmar Compra</h3>
            <div class="modal-message" id="modalMessage">
                <!-- Mensaje dinámico aquí -->
            </div>
            <div class="modal-actions">
                <a href="https://t.me/DaymelTech" class="btn btn-primary" id="telegramDirectLink" target="_blank" rel="noopener noreferrer">
                    <i class="fab fa-telegram"></i> Contactar por Telegram
                </a>
                <button class="btn btn-secondary close-modal-btn">Cancelar</button>
            </div>
        </div>
    </div>

    <!-- Modal de Anuncios -->
    <div class="announcements-modal" id="announcementsModal">
        <div class="announcements-content">
            <span class="close-announcements">&times;</span>
            <h3 class="announcements-title"><i class="fas fa-bullhorn"></i> Anuncios Recientes</h3>
            <div id="announcements-list">
                <div class="no-announcements">
                    <i class="fas fa-info-circle" style="font-size: 2rem; margin-bottom: 15px; display: block;"></i>
                    No hay anuncios disponibles en este momento.
                </div>
            </div>
        </div>
    </div>

    <!-- Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/9.6.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.6.0/firebase-database-compat.js"></script>

    <script>
        // Configuración de Firebase (reemplaza con tus credenciales)
        const firebaseConfig = {
            apiKey: "AIzaSyD3wwF3-E02dRP7Z8MH1k11UeR_pVqL66k",
            authDomain: "tienda-e1a2e.firebaseapp.com",
            databaseURL: "https://tienda-e1a2e-default-rtdb.firebaseio.com",
            projectId: "tienda-e1a2e",
            storageBucket: "tienda-e1a2e.appspot.com",
            messagingSenderId: "706488670782",
            appId: "1:706488670782:web:226c0feaa3cf3213b50f6f"
        };

        // Inicializar Firebase
        firebase.initializeApp(firebaseConfig);
        const database = firebase.database();

        // Referencia a los anuncios en la base de datos
        const announcementsRef = database.ref('announcements');
        
        // Elementos del DOM para el banner de anuncios
        const adminBanner = document.getElementById('adminBanner');
        const bannerTitle = document.getElementById('bannerTitle');
        const bannerMessage = document.getElementById('bannerMessage');
        const bannerTimestamp = document.getElementById('bannerTimestamp');
        const bannerLink = document.getElementById('bannerLink');
        const closeBanner = document.getElementById('closeBanner');
        
        // Variables para el sistema de anuncios
        const announcementsModal = document.getElementById('announcementsModal');
        const announcementsList = document.getElementById('announcements-list');
        const announcementsLink = document.getElementById('announcements-link');
        const announcementsBadge = document.getElementById('announcements-badge');
        let unreadAnnouncements = 0;

        // Comprobar si el usuario ha cerrado el banner recientemente
        function hasUserDismissedBanner(announcementId) {
            const dismissedBanners = JSON.parse(localStorage.getItem('dismissedBanners') || '[]');
            return dismissedBanners.includes(announcementId);
        }
        
        // Marcar banner como cerrado por el usuario
        function markBannerAsDismissed(announcementId) {
            const dismissedBanners = JSON.parse(localStorage.getItem('dismissedBanners') || '[]');
            if (!dismissedBanners.includes(announcementId)) {
                dismissedBanners.push(announcementId);
                localStorage.setItem('dismissedBanners', JSON.stringify(dismissedBanners));
            }
        }
        
        // Mostrar el banner con el anuncio
        function showAnnouncement(announcement) {
            if (hasUserDismissedBanner(announcement.id)) {
                return; // No mostrar si el usuario lo cerró recientemente
            }
            
            bannerTitle.textContent = announcement.title;
            bannerMessage.textContent = announcement.message;
            
            // Formatear fecha
            const date = new Date(announcement.timestamp);
            bannerTimestamp.textContent = `Publicado: ${date.toLocaleDateString()} a las ${date.toLocaleTimeString()}`;
            
            // Configurar enlace si existe
            if (announcement.link && announcement.link.trim() !== '') {
                bannerLink.href = announcement.link;
                bannerLink.style.display = 'inline-block';
            } else {
                bannerLink.style.display = 'none';
            }
            
            // Mostrar banner
            adminBanner.style.display = 'block';
            
            // Ajustar el margen superior del contenido principal
            document.body.style.marginTop = adminBanner.offsetHeight + 'px';
        }
        
        // Función para formatear la fecha
        function formatDate(timestamp) {
            const date = new Date(timestamp);
            return `${date.toLocaleDateString()} a las ${date.toLocaleTimeString()}`;
        }
        
        // Función para cargar los anuncios
        function loadAnnouncements() {
            announcementsRef.orderByChild('timestamp').on('value', (snapshot) => {
                const announcementsData = snapshot.val();
                const readAnnouncements = JSON.parse(localStorage.getItem('readAnnouncements') || '{}');
                
                if (announcementsData) {
                    // Convertir objeto a array y ordenar por fecha (más reciente primero)
                    const announcementsArray = Object.entries(announcementsData)
                        .map(([id, announcement]) => ({ id, ...announcement }))
                        .sort((a, b) => b.timestamp - a.timestamp);
                    
                    // Actualizar contador de anuncios no leídos
                    unreadAnnouncements = announcementsArray.filter(ann => !readAnnouncements[ann.id]).length;
                    updateBadge();
                    
                    // Mostrar anuncios en el modal
                    if (announcementsArray.length > 0) {
                        announcementsList.innerHTML = '';
                        
                        announcementsArray.forEach(announcement => {
                            const isRead = readAnnouncements[announcement.id];
                            const announcementElement = document.createElement('div');
                            announcementElement.className = `announcement-item ${isRead ? '' : 'unread'}`;
                            announcementElement.innerHTML = `
                                <h4 class="announcement-title">${announcement.title}</h4>
                                <p class="announcement-message">${announcement.message}</p>
                                ${announcement.link ? `<a href="${announcement.link}" target="_blank" class="announcement-link"><i class="fas fa-external-link-alt"></i> Ver más</a>` : ''}
                                <p class="announcement-timestamp">${formatDate(announcement.timestamp)}</p>
                            `;
                            announcementsList.appendChild(announcementElement);
                        });
                    }
                }
            });
        }

        // Función para actualizar el badge de notificaciones
        function updateBadge() {
            if (unreadAnnouncements > 0) {
                announcementsBadge.style.display = 'flex';
                announcementsBadge.textContent = unreadAnnouncements;
            } else {
                announcementsBadge.style.display = 'none';
            }
        }

        // Función para marcar anuncios como leídos
        function markAnnouncementsAsRead() {
            announcementsRef.once('value', (snapshot) => {
                const announcementsData = snapshot.val();
                const readAnnouncements = JSON.parse(localStorage.getItem('readAnnouncements') || '{}');
                
                if (announcementsData) {
                    Object.keys(announcementsData).forEach(id => {
                        readAnnouncements[id] = true;
                    });
                    
                    localStorage.setItem('readAnnouncements', JSON.stringify(readAnnouncements));
                    unreadAnnouncements = 0;
                    updateBadge();
                    
                    // Actualizar clases de elementos en el modal
                    document.querySelectorAll('.announcement-item').forEach(item => {
                        item.classList.remove('unread');
                    });
                }
            });
        }

        // Escuchar cambios en los anuncios
        announcementsRef.orderByChild('timestamp').limitToLast(1).on('value', (snapshot) => {
            const announcements = snapshot.val();
            if (announcements) {
                const latestAnnouncement = Object.values(announcements)[0];
                showAnnouncement(latestAnnouncement);
            }
        });
        
        // Cerrar banner
        closeBanner.addEventListener('click', () => {
            adminBanner.style.display = 'none';
            document.body.style.marginTop = '0';
            
            // Obtener el ID del anuncio actual para marcarlo como cerrado
            const announcementText = bannerTitle.textContent + bannerMessage.textContent;
            if (announcementText) {
                // Usamos un hash simple como ID único para este anuncio
                const announcementId = hashCode(announcementText);
                markBannerAsDismissed(announcementId);
            }
        });
        
        // Función para generar un hash simple de un string
        function hashCode(str) {
            let hash = 0;
            for (let i = 0; i < str.length; i++) {
                const char = str.charCodeAt(i);
                hash = ((hash << 5) - hash) + char;
                hash = hash & hash; // Convertir a 32bit integer
            }
            return hash;
        }
        
        // Ajustar el margen superior cuando se redimensiona la ventana
        window.addEventListener('resize', () => {
            if (adminBanner.style.display === 'block') {
                document.body.style.marginTop = adminBanner.offsetHeight + 'px';
            }
        });

        // Event listeners para el modal de anuncios
        announcementsLink.addEventListener('click', (e) => {
            e.preventDefault();
            announcementsModal.style.display = 'flex';
            document.body.style.overflow = 'hidden';
            markAnnouncementsAsRead();
        });

        document.querySelector('.close-announcements').addEventListener('click', () => {
            announcementsModal.style.display = 'none';
            document.body.style.overflow = '';
        });

        window.addEventListener('click', (e) => {
            if (e.target === announcementsModal) {
                announcementsModal.style.display = 'none';
                document.body.style.overflow = '';
            }
        });

        // Cargar anuncios al iniciar
        document.addEventListener('DOMContentLoaded', () => {
            loadAnnouncements();
            
            // Mostrar badge si hay anuncios no leídos
            const hasUnread = unreadAnnouncements > 0;
            if (hasUnread) {
                announcementsBadge.style.display = 'flex';
                announcementsBadge.textContent = unreadAnnouncements;
            }
        });

        // Mobile Menu Toggle
        const mobileMenu = document.getElementById('mobile-menu');
        const navLinks = document.getElementById('nav-links');
        const closeMenu = document.getElementById('close-menu');
        
        mobileMenu.addEventListener('click', () => {
            mobileMenu.classList.toggle('active');
            navLinks.classList.toggle('active');
            document.body.style.overflow = navLinks.classList.contains('active') ? 'hidden' : '';
        });
        
        closeMenu.addEventListener('click', () => {
            mobileMenu.classList.remove('active');
            navLinks.classList.remove('active');
            document.body.style.overflow = '';
        });
        
        // Close menu when clicking outside
        document.addEventListener('click', (e) => {
            if (!navLinks.contains(e.target) && !mobileMenu.contains(e.target)) {
                mobileMenu.classList.remove('active');
                navLinks.classList.remove('active');
                document.body.style.overflow = '';
            }
        });
        
        // Close menu when clicking a nav link
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('active');
                navLinks.classList.remove('active');
                document.body.style.overflow = '';
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            });
        });
        
        // Animation on scroll
        const animateElements = document.querySelectorAll('.animate');
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = 1;
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, { threshold: 0.1 });
        
        animateElements.forEach(element => {
            element.style.opacity = 0;
            element.style.transform = 'translateY(20px)';
            element.style.transition = 'all 0.6s ease-out';
            observer.observe(element);
        });

        // Back to Top Button
        const backToTopButton = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.add('visible');
            } else {
                backToTopButton.classList.remove('visible');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Purchase Modal Logic
        const modal = document.getElementById('purchaseModal');
        const modalMessage = document.getElementById('modalMessage');
        const closeModal = document.querySelector('.close-modal');
        const closeModalBtn = document.querySelector('.close-modal-btn');

        // Botones de compra
        document.querySelectorAll('.btn-buy').forEach(button => {
            button.addEventListener('click', function() {
                const service = this.getAttribute('data-service');
                const price = this.getAttribute('data-price');
                
                modalMessage.innerHTML = `
                    <div style="margin-bottom: 15px;">
                        <p style="font-weight: bold; margin-bottom: 8px; font-size: 1.1rem;">📋 Resumen de compra:</p>
                        <p><strong>Servicio:</strong> ${service}</p>
                        <p><strong>Precio:</strong> ${price}</p>
                    </div>
                    <p style="margin-bottom: 5px;">Serás redirigido al chat con @DaymelTech en Telegram para completar tu compra.</p>
                    <p style="font-size: 0.9rem; opacity: 0.8;"><i class="fas fa-info-circle"></i> Todos los servicios incluyen garantía y soporte.</p>
                `;
                
                // Actualizar el enlace de Telegram con información del servicio
                const telegramLink = document.getElementById('telegramDirectLink');
                telegramLink.href = `https://t.me/DaymelTech?text=Hola,%20estoy%20interesado%20en%20comprar%20el%20servicio%20${encodeURIComponent(service)}%20por%20${encodeURIComponent(price)}`;
                
                // Mostrar el modal
                modal.style.display = 'flex';
                document.body.style.overflow = 'hidden';
            });
        });

        // Cerrar modal
        closeModal.addEventListener('click', () => {
            modal.style.display = 'none';
            document.body.style.overflow = '';
        });

        closeModalBtn.addEventListener('click', () => {
            modal.style.display = 'none';
            document.body.style.overflow = '';
        });

        // Cerrar al hacer clic fuera del modal
        window.addEventListener('click', (e) => {
            if (e.target === modal) {
                modal.style.display = 'none';
                document.body.style.overflow = '';
            }
        });

        // Solución definitiva para el botón de Telegram
        document.getElementById('telegramDirectLink').addEventListener('click', function(e) {
            // Cerrar el modal cuando se hace clic en el enlace
            modal.style.display = 'none';
            document.body.style.overflow = '';
        });
    </script>
</body>
</html>
