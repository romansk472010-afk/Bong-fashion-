<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bong Fashion | Trendy Clothing Store in Salar</title>
  <style>
    :root {
      --primary: #111827;
      --accent: #e11d48;
      --whatsapp: #16a34a;
      --bg: #f9fafb;
      --card: #ffffff;
      --text: #1f2937;
      --muted: #6b7280;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', system-ui, sans-serif; }
    body { background: var(--bg); color: var(--text); line-height: 1.5; }

    /* Navbar */
    header {
      background: var(--primary);
      color: #fff;
      padding: 15px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    .brand h1 { font-size: 1.35rem; letter-spacing: 0.5px; }
    .brand span { color: var(--accent); }
    .header-actions { display: flex; gap: 8px; align-items: center; }
    .call-btn {
      background: var(--accent);
      color: #fff;
      text-decoration: none;
      padding: 8px 14px;
      border-radius: 6px;
      font-size: 0.85rem;
      font-weight: 600;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #1f2937 0%, #111827 100%);
      color: #fff;
      text-align: center;
      padding: 36px 20px;
    }
    .hero h2 { font-size: 1.75rem; margin-bottom: 8px; }
    .hero p { color: #d1d5db; max-width: 500px; margin: 0 auto 16px; font-size: 0.92rem; }
    .badge {
      display: inline-block;
      background: rgba(255,255,255,0.12);
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 0.8rem;
      color: #fde047;
    }

    /* Admin Panel */
    #adminPanel {
      display: none;
      max-width: 700px;
      margin: 20px auto;
      background: #fff;
      border: 2px solid var(--primary);
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }
    .admin-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 15px;
      border-bottom: 1px solid #e5e7eb;
      padding-bottom: 10px;
    }
    .admin-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
    }
    .admin-grid input, .admin-grid select {
      width: 100%;
      padding: 10px;
      border: 1px solid #d1d5db;
      border-radius: 8px;
      font-size: 0.9rem;
    }
    .full-width { grid-column: span 2; }
    .add-btn {
      background: var(--primary);
      color: #fff;
      border: none;
      padding: 11px;
      border-radius: 8px;
      font-weight: 600;
      cursor: pointer;
      width: 100%;
      margin-top: 10px;
    }
    .logout-btn {
      background: #ef4444;
      color: #fff;
      border: none;
      padding: 6px 12px;
      border-radius: 6px;
      font-size: 0.8rem;
      cursor: pointer;
    }

    /* Search & Filter Bar */
    .controls {
      max-width: 1100px;
      margin: 20px auto 5px;
      padding: 0 15px;
    }
    .search-box {
      width: 100%;
      max-width: 450px;
      display: block;
      margin: 0 auto 15px;
      padding: 11px 16px;
      border: 1px solid #d1d5db;
      border-radius: 25px;
      font-size: 0.95rem;
      outline: none;
      box-shadow: 0 2px 6px rgba(0,0,0,0.04);
    }
    .search-box:focus { border-color: var(--primary); }

    .filters {
      display: flex;
      justify-content: center;
      gap: 8px;
      flex-wrap: wrap;
    }
    .filter-btn {
      border: 1px solid #d1d5db;
      background: #fff;
      padding: 7px 15px;
      border-radius: 20px;
      cursor: pointer;
      font-size: 0.84rem;
      font-weight: 600;
      transition: 0.2s;
    }
    .filter-btn.active, .filter-btn:hover {
      background: var(--primary);
      color: #fff;
      border-color: var(--primary);
    }

    /* Product Grid */
    .container { max-width: 1100px; margin: 0 auto; padding: 15px; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 18px;
    }
    .card {
      background: var(--card);
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.06);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
      transition: transform 0.2s;
    }
    .card:hover { transform: translateY(-3px); }
    .card img {
      width: 100%;
      height: 230px;
      object-fit: cover;
      background: #e5e7eb;
    }
    .del-btn {
      position: absolute;
      top: 10px;
      right: 10px;
      background: rgba(220, 38, 38, 0.92);
      color: #fff;
      border: none;
      padding: 6px 10px;
      border-radius: 6px;
      font-size: 0.78rem;
      font-weight: 600;
      cursor: pointer;
      display: none;
    }
    body.admin-mode .del-btn { display: block; }

    .card-body { padding: 15px; }
    .tag {
      font-size: 0.72rem;
      text-transform: uppercase;
      color: var(--accent);
      font-weight: 700;
      letter-spacing: 0.5px;
    }
    .card-title { font-size: 1.05rem; font-weight: 700; margin: 4px 0; }
    .card-desc { font-size: 0.85rem; color: var(--muted); margin-bottom: 10px; }
    .price-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 10px;
    }
    .price { font-size: 1.15rem; font-weight: 800; color: var(--primary); }
    .wa-btn {
      background: var(--whatsapp);
      color: #fff;
      border: none;
      padding: 9px 14px;
      border-radius: 8px;
      font-size: 0.85rem;
      font-weight: 600;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }
    .wa-btn:hover { background: #15803d; }

    .empty-msg {
      text-align: center;
      grid-column: 1 / -1;
      padding: 40px;
      color: var(--muted);
    }

    /* Info Box */
    .info-section {
      background: #fff;
      margin: 25px auto;
      padding: 25px 20px;
      border-radius: 12px;
      max-width: 1100px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }
    .info-box h3 { font-size: 1rem; margin-bottom: 6px; color: var(--primary); }
    .info-box p { font-size: 0.88rem; color: var(--muted); }
    .map-link {
      display: inline-block;
      margin-top: 8px;
      color: var(--accent);
      font-weight: 600;
      text-decoration: none;
      font-size: 0.88rem;
    }

    footer {
      background: var(--primary);
      color: #9ca3af;
      text-align: center;
      padding: 18px;
      font-size: 0.82rem;
      margin-top: 20px;
    }
    .owner-link {
      color: #6b7280;
      text-decoration: underline;
      cursor: pointer;
      margin-left: 10px;
      background: none;
      border: none;
      font-size: 0.8rem;
    }

    @media (max-width: 500px) {
      .admin-grid { grid-template-columns: 1fr; }
      .full-width { grid-column: span 1; }
    }
  </style>
</head>
<body>

  <header>
    <div class="brand">
      <h1>Bong <span>Fashion</span></h1>
    </div>
    <div class="header-actions">
      <a href="tel:+919153786767" class="call-btn">📞 Call Shop</a>
    </div>
  </header>

  <section class="hero">
    <h2>Latest Styles in Salar</h2>
    <p>Trendy Men's, Women's & Festive Wear at best local prices. Search below & book directly on WhatsApp!</p>
    <div class="badge">🕒 Open: 11:00 AM – 9:30 PM (Fri Closed)</div>
  </section>

  <!-- Hidden Owner Admin Panel -->
  <section id="adminPanel">
    <div class="admin-header">
      <h3>⚙️ Shop Owner Admin Panel</h3>
      <button class="logout-btn" onclick="logoutAdmin()">Exit Admin</button>
    </div>
    <form onsubmit="addProduct(event)">
      <div class="admin-grid">
        <input type="text" id="pName" placeholder="Item Name (e.g. Cotton Kurti)" required />
        <input type="text" id="pPrice" placeholder="Price (e.g. ₹699)" required />
        <select id="pCat" required>
          <option value="men">Men's Wear</option>
          <option value="women">Women's Wear</option>
          <option value="festive">Festive & Ethnic</option>
        </select>
        <input type="url" id="pImg" placeholder="Image URL (https://...)" required />
        <input type="text" id="pDesc" class="full-width" placeholder="Details / Available Sizes (e.g. Sizes M, L, XL)" required />
      </div>
      <button type="submit" class="add-btn">+ Add Item to Catalog</button>
    </form>
  </section>

  <!-- Search & Filters -->
  <div class="controls">
    <input type="text" id="searchInput" class="search-box" placeholder="🔍 Search shirt, kurti, jeans, saree..." oninput="renderProducts()" />
    <div class="filters">
      <button class="filter-btn active" onclick="setCategory('all', this)">All Collection</button>
      <button class="filter-btn" onclick="setCategory('men', this)">Men's Wear</button>
      <button class="filter-btn" onclick="setCategory('women', this)">Women's Wear</button>
      <button class="filter-btn" onclick="setCategory('festive', this)">Festive & Ethnic</button>
    </div>
  </div>

  <main class="container">
    <div class="grid" id="productGrid"></div>
  </main>

  <section class="info-section">
    <div class="info-box">
      <h3>📍 Store Address</h3>
      <p>Uttar Hazampara, Salar, West Bengal 742401</p>
      <a href="https://maps.app.goo.gl/yQhnMdDkPEDSVqnT6" target="_blank" class="map-link">Open in Google Maps →</a>
    </div>
    <div class="info-box">
      <h3>⏰ Opening Hours</h3>
      <p>Saturday – Thursday: 11:00 AM – 9:30 PM<br>Friday: Closed</p>
    </div>
    <div class="info-box">
      <h3>💬 Direct Order & Inquiry</h3>
      <p>Phone / WhatsApp: +91 91537 86767<br>Fast local pickup & delivery inquiry available.</p>
    </div>
  </section>

  <footer>
    © 2026 Bong Fashion, Salar • Digital Storefront
    <button class="owner-link" onclick="openAdmin()">🔒 Owner Login</button>
  </footer>

  <script>
    const SHOP_PHONE = "919153786767";
    const ADMIN_PIN = "1234"; // Demo PIN
    let currentCategory = "all";

    const defaultProducts = [
      {
        id: 1,
        name: "Men's Casual Printed Shirt",
        category: "men",
        tag: "Men's Wear",
        price: "₹599",
        desc: "Comfortable cotton blend, sizes M, L, XL available.",
        img: "https://images.unsplash.com/photo-1596755094514-f87e34085b2c?auto=format&fit=crop&w=600&q=80"
      },
      {
        id: 2,
        name: "Women's Stylish Kurti Set",
        category: "women",
        tag: "Women's Wear",
        price: "₹799",
        desc: "Soft breathable fabric with modern print & dupatta.",
        img: "https://images.unsplash.com/photo-1583391733956-6c78276477e2?auto=format&fit=crop&w=600&q=80"
      },
      {
        id: 3,
        name: "Slim Fit Denim Jeans",
        category: "men",
        tag: "Men's Wear",
        price: "₹899",
        desc: "Stretchable dark blue denim, sizes 28 to 36.",
        img: "https://images.unsplash.com/photo-1542272604-787c3835535d?auto=format&fit=crop&w=600&q=80"
      },
      {
        id: 4,
        name: "Festive Designer Saree",
        category: "festive",
        tag: "Festive & Ethnic",
        price: "₹1,299",
        desc: "Elegant traditional border work, perfect for occasions.",
        img: "https://images.unsplash.com/photo-1610030469983-98e550d6193c?auto=format&fit=crop&w=600&q=80"
      },
      {
        id: 5,
        name: "Oversized Streetwear T-Shirt",
        category: "men",
        tag: "Men's Wear",
        price: "₹449",
        desc: "100% pure cotton drop-shoulder tee in multiple colors.",
        img: "https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=600&q=80"
      },
      {
        id: 6,
        name: "Women's Western Top",
        category: "women",
        tag: "Women's Wear",
        price: "₹499",
        desc: "Trendy daily & party wear top in S, M, L sizes.",
        img: "https://images.unsplash.com/photo-1551163943-3f6a855d1153?auto=format&fit=crop&w=600&q=80"
      }
    ];

    let products = JSON.parse(localStorage.getItem("bongFashionProducts")) || defaultProducts;

    function saveProducts() {
      localStorage.setItem("bongFashionProducts", JSON.stringify(products));
    }

    function renderProducts() {
      const grid = document.getElementById("productGrid");
      const query = document.getElementById("searchInput").value.toLowerCase().trim();
      grid.innerHTML = "";

      const filtered = products.filter(p => {
        const matchesCat = currentCategory === "all" || p.category === currentCategory;
        const matchesSearch = p.name.toLowerCase().includes(query) || p.desc.toLowerCase().includes(query);
        return matchesCat && matchesSearch;
      });

      if (filtered.length === 0) {
        grid.innerHTML = `<div class="empty-msg">Koi item nahi mila. Dusra keyword search karein!</div>`;
        return;
      }

      filtered.forEach(item => {
        const msg = encodeURIComponent(`Hello Bong Fashion! Mujhe yeh item pasand aaya hai:\n*${item.name}* (${item.price})\nKya yeh stock mein available hai?`);
        const waUrl = `https://wa.me/${SHOP_PHONE}?text=${msg}`;

        grid.innerHTML += `
          <div class="card">
            <button class="del-btn" onclick="deleteProduct(${item.id})">🗑️ Delete</button>
            <img src="${item.img}" alt="${item.name}" loading="lazy" onerror="this.src='https://via.placeholder.com/400x300?text=Bong+Fashion'" />
            <div class="card-body">
              <div class="tag">${item.tag}</div>
              <div class="card-title">${item.name}</div>
              <div class="card-desc">${item.desc}</div>
              <div class="price-row">
                <span class="price">${item.price}</span>
                <a href="${waUrl}" target="_blank" class="wa-btn">WhatsApp Order</a>
              </div>
            </div>
          </div>
        `;
      });
    }

    function setCategory(category, btn) {
      currentCategory = category;
      document.querySelectorAll(".filter-btn").forEach(b => b.classList.remove("active"));
      btn.classList.add("active");
      renderProducts();
    }

    // Admin Functions
    function openAdmin() {
      const pin = prompt("Enter Shop Owner PIN (Demo PIN: 1234):");
      if (pin === ADMIN_PIN) {
        document.getElementById("adminPanel").style.display = "block";
        document.body.classList.add("admin-mode");
        window.scrollTo({ top: 0, behavior: "smooth" });
      } else if (pin !== null) {
        alert("Galat PIN!");
      }
    }

    function logoutAdmin() {
      document.getElementById("adminPanel").style.display = "none";
      document.body.classList.remove("admin-mode");
    }

    function addProduct(e) {
      e.preventDefault();
      const cat = document.getElementById("pCat").value;
      const tagMap = { men: "Men's Wear", women: "Women's Wear", festive: "Festive & Ethnic" };

      const newItem = {
        id: Date.now(),
        name: document.getElementById("pName").value.trim(),
        price: document.getElementById("pPrice").value.trim(),
        category: cat,
        tag: tagMap[cat],
        img: document.getElementById("pImg").value.trim(),
        desc: document.getElementById("pDesc").value.trim()
      };

      products.unshift(newItem);
      saveProducts();
      renderProducts();
      e.target.reset();
      alert("Naya item catalog mein add ho gaya!");
    }

    function deleteProduct(id) {
      if (confirm("Kya aap is item ko hatana chahte hain?")) {
        products = products.filter(p => p.id !== id);
        saveProducts();
        renderProducts();
      }
    }

    renderProducts();
  </script>
</body>
</html>
