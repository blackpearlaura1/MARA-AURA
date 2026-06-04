<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARA AURA</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Playfair+Display:wght@700;800&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <i class="fas fa-sparkles"></i>
                <span>MARA AURA</span>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#featured">Featured</a></li>
                <li><a href="#partners">Partners</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1 class="hero-title">Welcome to MARA AURA</h1>
            <p class="hero-subtitle">Discover Exquisite Products from Around the World</p>
            <p class="hero-description">Luxury Fashion • Beauty • Electronics • Home Essentials</p>
            <button class="cta-button" onclick="document.getElementById('categories').scrollIntoView({behavior: 'smooth'})">
                Explore Now
            </button>
        </div>
        <div class="hero-background">
            <div class="gradient-blob blob-1"></div>
            <div class="gradient-blob blob-2"></div>
        </div>
    </section>

    <!-- Affiliate Partners Section -->
    <section id="partners" class="partners-section">
        <h2>Our Trusted Partners</h2>
        <p class="section-subtitle">Shop from the world's leading retailers</p>
        <div class="partners-grid">
            <a href="https://amazon.com" target="_blank" class="partner-card amazon">
                <i class="fab fa-amazon"></i>
                <span>Amazon</span>
            </a>
            <a href="https://temu.com" target="_blank" class="partner-card temu">
                <i class="fas fa-shopping-bag"></i>
                <span>Temu</span>
            </a>
            <a href="https://jumia.com.ng" target="_blank" class="partner-card jumia">
                <i class="fas fa-store"></i>
                <span>Jumia</span>
            </a>
            <a href="https://alibaba.com" target="_blank" class="partner-card alibaba">
                <i class="fas fa-globe"></i>
                <span>Alibaba</span>
            </a>
            <a href="https://aliexpress.com" target="_blank" class="partner-card aliexpress">
                <i class="fas fa-cube"></i>
                <span>AliExpress</span>
            </a>
            <a href="https://shein.com" target="_blank" class="partner-card shein">
                <i class="fas fa-heart"></i>
                <span>Shein</span>
            </a>
        </div>
    </section>

    <!-- Categories Section -->
    <section id="categories" class="categories">
        <h2>Shop by Category</h2>
        <p class="section-subtitle">Find exactly what you're looking for</p>
        <div class="categories-grid">
            <div class="category-card" onclick="showCategory('fashion')">
                <div class="category-image">
                    <i class="fas fa-shirt"></i>
                </div>
                <h3>Fashion & Clothing</h3>
                <p>Trendy outfits & styles</p>
            </div>
            <div class="category-card" onclick="showCategory('beauty')">
                <div class="category-image">
                    <i class="fas fa-spa"></i>
                </div>
                <h3>Beauty & Cosmetics</h3>
                <p>Skincare & makeup</p>
            </div>
            <div class="category-card" onclick="showCategory('electronics')">
                <div class="category-image">
                    <i class="fas fa-mobile-alt"></i>
                </div>
                <h3>Electronics</h3>
                <p>Tech gadgets</p>
            </div>
            <div class="category-card" onclick="showCategory('kitchen')">
                <div class="category-image">
                    <i class="fas fa-utensils"></i>
                </div>
                <h3>Kitchen & Home</h3>
                <p>Home essentials</p>
            </div>
            <div class="category-card" onclick="showCategory('bags')">
                <div class="category-image">
                    <i class="fas fa-backpack"></i>
                </div>
                <h3>Bags & Accessories</h3>
                <p>Stylish bags</p>
            </div>
            <div class="category-card" onclick="showCategory('slippers')">
                <div class="category-image">
                    <i class="fas fa-shoe-prints"></i>
                </div>
                <h3>Footwear</h3>
                <p>Slippers & shoes</p>
            </div>
        </div>
    </section>

    <!-- Featured Products Section -->
    <section id="featured" class="featured-products">
        <h2>Featured Collections</h2>
        <p class="section-subtitle">Handpicked selections just for you</p>
        
        <!-- Fashion Products -->
        <div class="products-category" id="fashion-category" style="display: none;">
            <h3>Fashion & Clothing</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-dress"></i>
                    </div>
                    <h4>Summer Dress Collection</h4>
                    <p class="price">From $15.99</p>
                    <a href="https://amazon.com/s?k=summer+dresses" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-shirt"></i>
                    </div>
                    <h4>Casual T-Shirt Set</h4>
                    <p class="price">From $8.99</p>
                    <a href="https://temu.com" target="_blank" class="shop-btn">
                        <i class="fas fa-shopping-bag"></i> Shop on Temu
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-vest"></i>
                    </div>
                    <h4>Stylish Jacket</h4>
                    <p class="price">From $24.99</p>
                    <a href="https://shein.com" target="_blank" class="shop-btn">
                        <i class="fas fa-heart"></i> Shop on Shein
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-person-dress"></i>
                    </div>
                    <h4>Elegant Gown</h4>
                    <p class="price">From $35.99</p>
                    <a href="https://aliexpress.com" target="_blank" class="shop-btn">
                        <i class="fas fa-cube"></i> Shop on AliExpress
                    </a>
                </div>
            </div>
        </div>

        <!-- Beauty Products -->
        <div class="products-category" id="beauty-category" style="display: none;">
            <h3>Beauty & Cosmetics</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image beauty">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h4>Makeup Brush Set</h4>
                    <p class="price">From $9.99</p>
                    <a href="https://amazon.com/s?k=makeup+brushes" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image beauty">
                        <i class="fas fa-droplet"></i>
                    </div>
                    <h4>Premium Skincare Kit</h4>
                    <p class="price">From $19.99</p>
                    <a href="https://alibaba.com" target="_blank" class="shop-btn">
                        <i class="fas fa-globe"></i> Shop on Alibaba
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image beauty">
                        <i class="fas fa-flower"></i>
                    </div>
                    <h4>Natural Lip Balm</h4>
                    <p class="price">From $4.99</p>
                    <a href="https://jumia.com.ng" target="_blank" class="shop-btn">
                        <i class="fas fa-store"></i> Shop on Jumia
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image beauty">
                        <i class="fas fa-gem"></i>
                    </div>
                    <h4>Luxury Perfume</h4>
                    <p class="price">From $29.99</p>
                    <a href="https://temu.com" target="_blank" class="shop-btn">
                        <i class="fas fa-shopping-bag"></i> Shop on Temu
                    </a>
                </div>
            </div>
        </div>

        <!-- Electronics Products -->
        <div class="products-category" id="electronics-category" style="display: none;">
            <h3>Electronics & Gadgets</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image electronics">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h4>Wireless Earbuds</h4>
                    <p class="price">From $22.99</p>
                    <a href="https://amazon.com/s?k=wireless+earbuds" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image electronics">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h4>Smart LED Lights</h4>
                    <p class="price">From $15.99</p>
                    <a href="https://aliexpress.com" target="_blank" class="shop-btn">
                        <i class="fas fa-cube"></i> Shop on AliExpress
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image electronics">
                        <i class="fas fa-phone"></i>
                    </div>
                    <h4>Phone Stand & Charger</h4>
                    <p class="price">From $12.99</p>
                    <a href="https://temu.com" target="_blank" class="shop-btn">
                        <i class="fas fa-shopping-bag"></i> Shop on Temu
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image electronics">
                        <i class="fas fa-headphones"></i>
                    </div>
                    <h4>Bluetooth Speaker</h4>
                    <p class="price">From $28.99</p>
                    <a href="https://jumia.com.ng" target="_blank" class="shop-btn">
                        <i class="fas fa-store"></i> Shop on Jumia
                    </a>
                </div>
            </div>
        </div>

        <!-- Kitchen Products -->
        <div class="products-category" id="kitchen-category" style="display: none;">
            <h3>Kitchen & Home Essentials</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image kitchen">
                        <i class="fas fa-blender"></i>
                    </div>
                    <h4>Blender Set</h4>
                    <p class="price">From $34.99</p>
                    <a href="https://amazon.com/s?k=blender" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image kitchen">
                        <i class="fas fa-pot-food"></i>
                    </div>
                    <h4>Non-stick Cookware</h4>
                    <p class="price">From $42.99</p>
                    <a href="https://alibaba.com" target="_blank" class="shop-btn">
                        <i class="fas fa-globe"></i> Shop on Alibaba
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image kitchen">
                        <i class="fas fa-knife"></i>
                    </div>
                    <h4>Chef Knife Set</h4>
                    <p class="price">From $19.99</p>
                    <a href="https://aliexpress.com" target="_blank" class="shop-btn">
                        <i class="fas fa-cube"></i> Shop on AliExpress
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image kitchen">
                        <i class="fas fa-mug-hot"></i>
                    </div>
                    <h4>Coffee Maker</h4>
                    <p class="price">From $24.99</p>
                    <a href="https://temu.com" target="_blank" class="shop-btn">
                        <i class="fas fa-shopping-bag"></i> Shop on Temu
                    </a>
                </div>
            </div>
        </div>

        <!-- Bags & Accessories -->
        <div class="products-category" id="bags-category" style="display: none;">
            <h3>Bags & Accessories</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image bags">
                        <i class="fas fa-bag-shopping"></i>
                    </div>
                    <h4>Designer Handbag</h4>
                    <p class="price">From $38.99</p>
                    <a href="https://amazon.com/s?k=handbags" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image bags">
                        <i class="fas fa-backpack"></i>
                    </div>
                    <h4>Travel Backpack</h4>
                    <p class="price">From $32.99</p>
                    <a href="https://shein.com" target="_blank" class="shop-btn">
                        <i class="fas fa-heart"></i> Shop on Shein
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image bags">
                        <i class="fas fa-suitcase"></i>
                    </div>
                    <h4>Luggage Set</h4>
                    <p class="price">From $89.99</p>
                    <a href="https://aliexpress.com" target="_blank" class="shop-btn">
                        <i class="fas fa-cube"></i> Shop on AliExpress
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image bags">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <h4>Work Briefcase</h4>
                    <p class="price">From $45.99</p>
                    <a href="https://jumia.com.ng" target="_blank" class="shop-btn">
                        <i class="fas fa-store"></i> Shop on Jumia
                    </a>
                </div>
            </div>
        </div>

        <!-- Slippers & Footwear -->
        <div class="products-category" id="slippers-category" style="display: none;">
            <h3>Footwear & Slippers</h3>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image slippers">
                        <i class="fas fa-slipper"></i>
                    </div>
                    <h4>Comfort Slippers</h4>
                    <p class="price">From $9.99</p>
                    <a href="https://amazon.com/s?k=slippers" target="_blank" class="shop-btn">
                        <i class="fab fa-amazon"></i> Shop on Amazon
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image slippers">
                        <i class="fas fa-shoe-prints"></i>
                    </div>
                    <h4>Casual Sneakers</h4>
                    <p class="price">From $28.99</p>
                    <a href="https://temu.com" target="_blank" class="shop-btn">
                        <i class="fas fa-shopping-bag"></i> Shop on Temu
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image slippers">
                        <i class="fas fa-loafer"></i>
                    </div>
                    <h4>Elegant Loafers</h4>
                    <p class="price">From $35.99</p>
                    <a href="https://shein.com" target="_blank" class="shop-btn">
                        <i class="fas fa-heart"></i> Shop on Shein
                    </a>
                </div>
                <div class="product-card">
                    <div class="product-image slippers">
                        <i class="fas fa-hiking"></i>
                    </div>
                    <h4>Athletic Shoes</h4>
                    <p class="price">From $42.99</p>
                    <a href="https://alibaba.com" target="_blank" class="shop-btn">
                        <i class="fas fa-globe"></i> Shop on Alibaba
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter">
        <div class="newsletter-content">
            <h2>Stay Updated</h2>
            <p>Get exclusive deals and new arrivals delivered to your inbox</p>
            <form class="newsletter-form">
                <input type="email" placeholder="Enter your email" required>
                <button type="submit">Subscribe</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="footer">
        <div class="footer-content">
            <div class="footer-section">
                <h4>About MARA AURA</h4>
                <p>Your premier destination for curated products from the world's leading retailers.</p>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-tiktok"></i></a>
                </div>
            </div>
            <div class="footer-section">
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#categories">Categories</a></li>
                    <li><a href="#featured">Shop</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Affiliate Partners</h4>
                <ul>
                    <li><a href="https://amazon.com" target="_blank">Amazon</a></li>
                    <li><a href="https://temu.com" target="_blank">Temu</a></li>
                    <li><a href="https://jumia.com.ng" target="_blank">Jumia</a></li>
                    <li><a href="https://alibaba.com" target="_blank">Alibaba</a></li>
                    <li><a href="https://aliexpress.com" target="_blank">AliExpress</a></li>
                    <li><a href="https://shein.com" target="_blank">Shein</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Contact</h4>
                <p><i class="fas fa-envelope"></i> info@maraaura.com</p>
                <p><i class="fas fa-phone"></i> +1 (555) 123-4567</p>
                <p><i class="fas fa-map-marker-alt"></i> Global Operations</p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 MARA AURA. All rights reserved. | Premium Dropshipping Experience</p>
        </div>
    </footer>

    <script src="script.js"></script> :root {
    --primary-color: #8B5CF6;
    --secondary-color: #EC4899;
    --accent-color: #F59E0B;
    /* ... more colors ... */
}<div class="product-card">
    <div class="product-image">
        <i class="fas fa-icon"></i>
    </div>
    <h4>Product Name</h4>
    <p class="price">From $X.XX</p>
    <a href="affiliate-link" target="_blank" class="shop-btn">
        <i class="fab fa-platform"></i> Shop
    </a>
</div>
</body>
</html>
