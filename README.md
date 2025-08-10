<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>New India Traders - Locomotive Parts & Railway Equipment Supplier</title>
    <meta name="description" content="Leading supplier of locomotive parts and railway equipment in India. Specializing in brake components, electrical systems, engine parts, wheels & axles, coupling systems, and safety equipment.">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9fafb;
        }

        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #1E3A8A 0%, #374151 100%);
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #F59E0B;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
            margin: 0;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            transition: color 0.3s ease;
            font-weight: 500;
        }

        .nav-links a:hover {
            color: #F59E0B;
        }

        .nav-actions {
            display: flex;
            gap: 1rem;
            align-items: center;
        }

        /* Button Styles */
        .btn {
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            font-weight: 600;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            cursor: pointer;
            font-size: 0.875rem;
            text-align: center;
        }

        .btn-primary {
            background-color: #1E3A8A;
            color: white;
        }

        .btn-primary:hover {
            background-color: #1E40AF;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(30, 58, 138, 0.3);
        }

        .btn-secondary {
            background-color: transparent;
            color: #1E3A8A;
            border: 2px solid #1E3A8A;
        }

        .btn-secondary:hover {
            background-color: #1E3A8A;
            color: white;
            transform: translateY(-2px);
        }

        .btn-outline {
            background-color: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn-outline:hover {
            background-color: white;
            color: #1E3A8A;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #1E3A8A 0%, #374151 100%);
            color: white;
            padding: 6rem 0;
            text-align: center;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            font-weight: bold;
            margin-bottom: 1.5rem;
            line-height: 1.2;
        }

        .hero-content p {
            font-size: 1.25rem;
            margin-bottom: 2.5rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            opacity: 0.9;
        }

        .hero-actions {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        /* Products Section */
        .products {
            padding: 6rem 0;
            background: white;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            font-weight: bold;
            color: #374151;
            margin-bottom: 1rem;
        }

        .section-subtitle {
            text-align: center;
            font-size: 1.125rem;
            color: #6B7280;
            margin-bottom: 4rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .product-card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            border: 1px solid #E5E7EB;
            transition: all 0.3s ease;
            text-align: center;
        }

        .product-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
            border-color: #1E3A8A;
        }

        .product-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, #1E3A8A, #374151);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1.5rem;
            font-size: 2rem;
            color: white;
        }

        .product-card h3 {
            font-size: 1.5rem;
            font-weight: bold;
            color: #374151;
            margin-bottom: 1rem;
        }

        .product-card p {
            color: #6B7280;
            line-height: 1.6;
        }

        /* Quotation Section */
        .quotation {
            padding: 6rem 0;
            background: #f9fafb;
        }

        .form-container {
            max-width: 100%;
            margin: 0 auto;
            background: white;
            border-radius: 12px;
            padding: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            overflow: hidden;
        }

        /* Responsive iframe container */
        .iframe-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-bottom: 120%; /* Default aspect ratio for forms */
            overflow: hidden;
            border-radius: 8px;
        }

        .iframe-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
            border-radius: 8px;
            background: #f9fafb;
        }

        /* Footer */
        .footer {
            background: #374151;
            color: white;
            padding: 3rem 0;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .footer-section h3 {
            font-size: 1.25rem;
            font-weight: bold;
            margin-bottom: 1rem;
            color: #F59E0B;
        }

        .footer-section p,
        .footer-section li {
            color: #D1D5DB;
            line-height: 1.6;
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 0.5rem;
        }

        .footer-section a {
            color: #D1D5DB;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-section a:hover {
            color: #F59E0B;
        }

        .footer-bottom {
            border-top: 1px solid #4B5563;
            margin-top: 2rem;
            padding-top: 2rem;
            text-align: center;
            color: #9CA3AF;
        }

        /* Tablet adjustments */
        @media (max-width: 1024px) and (min-width: 769px) {
            .iframe-container {
                padding-bottom: 110%; /* Adjust for tablet size */
            }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .nav-container {
                flex-direction: column;
                gap: 1rem;
            }

            .nav-actions {
                justify-content: center;
            }

            .hero-content h1 {
                font-size: 2.5rem;
            }

            .hero-actions {
                flex-direction: column;
                align-items: center;
            }

            .section-title {
                font-size: 1.875rem;
            }

            .products-grid {
                grid-template-columns: 1fr;
            }

            .form-container {
                margin: 0 20px;
                padding: 0.5rem;
            }

            .footer-content {
                grid-template-columns: 1fr;
                text-align: center;
            }

            /* Mobile iframe adjustments */
            .iframe-container {
                padding-bottom: 140%; /* Increase height for mobile forms */
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }

            .hero {
                padding: 3rem 0;
            }

            .hero-content h1 {
                font-size: 2rem;
            }

            .products,
            .quotation {
                padding: 3rem 0;
            }

            .btn {
                padding: 10px 20px;
                font-size: 0.825rem;
            }

            .form-container {
                padding: 0.25rem;
                margin: 0 5px;
            }
            
            /* Extra height for small mobile screens */
            .iframe-container {
                padding-bottom: 160%; /* Even more height for small screens */
            }
        }

        /* Smooth scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Loading animation */
        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid #f3f3f3;
            border-top: 3px solid #1E3A8A;
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <nav class="nav-container">
                <div class="logo">New India Traders</div>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#quotation">Get Quote</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="nav-actions">
                    <a href="#quotation" class="btn btn-outline">Request Quote</a>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Premium Locomotive Parts & Railway Equipment</h1>
                <p>Your trusted partner for high-quality railway components, ensuring safe and efficient rail operations across India</p>
                <div class="hero-actions">
                    <a href="#products" class="btn btn-primary">Explore Products</a>
                    <a href="#quotation" class="btn btn-outline">Get Quote</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <div class="container">
            <h2 class="section-title">Our Product Range</h2>
            <p class="section-subtitle">
                Comprehensive selection of locomotive parts and railway equipment for all your operational needs
            </p>
            
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-icon">🛠️</div>
                    <h3>Brake Components</h3>
                    <p>High-performance brake systems, brake pads, discs, and cylinders ensuring maximum safety and reliability for locomotive operations.</p>
                </div>
                
                <div class="product-card">
                    <div class="product-icon">⚡</div>
                    <h3>Electrical Systems</h3>
                    <p>Advanced electrical components including motors, generators, control panels, and wiring harnesses for efficient locomotive power management.</p>
                </div>
                
                <div class="product-card">
                    <div class="product-icon">🔧</div>
                    <h3>Engine Parts</h3>
                    <p>Premium engine components, pistons, valves, filters, and gaskets designed for durability and optimal locomotive performance.</p>
                </div>
                
                <div class="product-card">
                    <div class="product-icon">🚂</div>
                    <h3>Wheels & Axles</h3>
                    <p>Precision-engineered wheels, axles, and bearings manufactured to railway standards for smooth and safe train operations.</p>
                </div>
                
                <div class="product-card">
                    <div class="product-icon">🔗</div>
                    <h3>Coupling Systems</h3>
                    <p>Robust coupling mechanisms and connecting hardware designed for secure locomotive-to-car connections in all operating conditions.</p>
                </div>
                
                <div class="product-card">
                    <div class="product-icon">🛡️</div>
                    <h3>Safety Equipment</h3>
                    <p>Comprehensive safety systems including signals, alarms, emergency equipment, and protective gear for railway personnel.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Quotation Section -->
    <section id="quotation" class="quotation">
        <div class="container">
            <h2 class="section-title">Request a Quote</h2>
            <p class="section-subtitle">
                Get competitive pricing for your locomotive parts requirements
            </p>

            <div class="form-container">
                <div class="iframe-container">
                    <iframe 
                        src="https://docs.google.com/forms/d/e/1FAIpQLScs1VZGD0mqOkn434t_xc18XRz_uyeRzh1Y4Ngd9v8IAbQ2Ww/viewform?embedded=true" 
                        frameborder="0" 
                        marginheight="0" 
                        marginwidth="0"
                        title="Quotation Request Form">
                        Loading…
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>New India Traders</h3>
                    <p>Leading supplier of locomotive parts and railway equipment, committed to quality, reliability, and customer satisfaction.</p>
                </div>
                
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#quotation">Get Quote</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Products</h3>
                    <ul>
                        <li>Brake Components</li>
                        <li>Electrical Systems</li>
                        <li>Engine Parts</li>
                        <li>Wheels & Axles</li>
                        <li>Coupling Systems</li>
                        <li>Safety Equipment</li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Contact Info</h3>
                    <p>📧 info@newindiatraders.com</p>
                    <p>📞 +91 XXX XXX XXXX</p>
                    <p>📍 India</p>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2024 New India Traders. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
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

        // Add loading state to iframe
        window.addEventListener('load', function() {
            const iframe = document.querySelector('iframe');
            if (iframe) {
                iframe.addEventListener('load', function() {
                    console.log('Google Form loaded successfully');
                });
            }
        });
    </script>
</body>
</html>
