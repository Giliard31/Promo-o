<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Ofertas Imperdíveis</title>
  
  <!-- PWA -->
  <link rel="manifest" href="data:application/json;base64,ewogICJuYW1lIjogIk9mZXJ0YXMgSW1wZXJkbsOtdmVpcyIsCiAgInNob3J0X25hbWUiOiAiT2ZlcnRhcyIsCiAgImRlc2NyaXB0aW9uIjogIk9mZXJ0YXMgaW5jcmVkbsOtddmVpcyBkZSBwcm9kdXRvcyBwYXJhIHZvY8OhcyIsCiAgInN0YXJ0X3VybCI6ICIvIiwKICAiZGlzcGxheSI6ICJzdGFuZGFsb25lIiwKICAiYmFja2dyb3VuZF9jb2xvciI6ICIjZjVmNWY1IiwKICAidGhlbWVfY29sb3IiOiAiRUU0RFREIn0=">
  <meta name="theme-color" content="#EE4D2D">
  <meta name="apple-mobile-web-app-capable" content="yes">
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      min-height: 100vh;
      padding-bottom: 20px;
    }

    /* Cabeçalho */
    header {
      background: linear-gradient(to right, #EE4D2D, #FF6A00);
      padding: 12px 16px;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .header-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 10px;
    }

    .logo {
      color: white;
      font-size: 20px;
      font-weight: 700;
    }

    .login-header-btn {
      background: white;
      color: #EE4D2D;
      border: none;
      padding: 6px 16px;
      border-radius: 4px;
      font-size: 14px;
      font-weight: 600;
      cursor: pointer;
    }

    .user-info {
      color: white;
      font-size: 13px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .logout-btn {
      background: rgba(255,255,255,0.2);
      color: white;
      border: none;
      padding: 4px 8px;
      border-radius: 3px;
      font-size: 12px;
      cursor: pointer;
    }

    .search-bar {
      display: flex;
      background: white;
      border-radius: 2px;
      padding: 8px 12px;
      align-items: center;
      margin-top: 8px;
    }

    .search-bar input {
      border: none;
      outline: none;
      flex: 1;
      font-size: 14px;
      width: 100%;
    }

    .section-title {
      padding: 12px 16px;
      font-size: 16px;
      font-weight: 600;
      color: #333;
    }

    /* Grade de Produtos */
    .products-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
      padding: 12px;
    }

    .product-card {
      background: white;
      border-radius: 4px;
      overflow: hidden;
      box-shadow: 0 1px 3px rgba(0,0,0,0.08);
    }

    .product-image {
      width: 100%;
      aspect-ratio: 1;
      background: #fafafa;
      object-fit: cover;
      cursor: pointer;
    }

    .product-info {
      padding: 10px;
    }

    .product-name {
      font-size: 13px;
      color: #333;
      line-height: 1.4;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      overflow: hidden;
      margin-bottom: 6px;
    }

    .product-price {
      color: #EE4D2D;
      font-size: 16px;
      font-weight: 700;
    }

    .product-discount {
      display: inline-block;
      background: #EE4D2D;
      color: white;
      font-size: 10px;
      padding: 2px 4px;
      border-radius: 2px;
      margin-left: 6px;
    }

    .product-timer {
      background: #FFF0EB;
      color: #EE4D2D;
      font-size: 11px;
      padding: 4px 6px;
      border-radius: 3px;
      margin-top: 6px;
      display: flex;
      align-items: center;
      gap: 4px;
    }

    .product-timer span.time {
      font-weight: 700;
      font-size: 13px;
    }

    .buy-btn {
      width: 100%;
      background: #EE4D2D;
      color: white;
      border: none;
      padding: 8px;
      border-radius: 3px;
      margin-top: 8px;
      font-size: 13px;
      font-weight: 600;
      cursor: pointer;
    }

    /* Modal Imagem */
    .image-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.9);
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      z-index: 200;
      padding: 20px;
    }

    .image-modal.show { display: flex; }
    .image-modal img { max-width: 100%; max-height: 60vh; border-radius: 4px; margin-bottom: 15px; }
    .modal-close { position: absolute; top: 15px; right: 20px; color: white; font-size: 30px; cursor: pointer; }
    .modal-product-name { color: white; font-size: 16px; text-align: center; margin-bottom: 10px; }
    .modal-timer { background: #EE4D2D; color: white; padding: 10px 20px; border-radius: 4px; font-size: 18px; font-weight: 700; margin-bottom: 15px; }
    .modal-buy-btn { background: #EE4D2D; color: white; border: none; padding: 12px 40px; font-size: 16px; border-radius: 4px; cursor: pointer; font-weight: 600; }

    /* Tela de Login/Cadastro */
    .auth-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.5);
      display: none;
      align-items: center;
      justify-content: center;
      z-index: 300;
      padding: 20px;
    }

    .auth-modal.show { display: flex; }
    .auth-box { background: white; padding: 25px; border-radius: 8px; width: 100%; max-width: 350px; }
    .auth-box h3 { text-align: center; margin-bottom: 20px; color: #333; }
    .auth-box input { width: 100%; padding: 12px; margin-bottom: 12px; border: 1px solid #ddd; border-radius: 4px; font-size: 14px; }
    .auth-btn { width: 100%; background: #EE4D2D; color: white; border: none; padding: 12px; border-radius: 4px; font-size: 16px; cursor: pointer; font-weight: 600; margin-top: 5px; }
    .auth-switch { text-align: center; margin-top: 15px; font-size: 13px; color: #666; cursor: pointer; }
    .close-auth { text-align: center; margin-top: 10px; color: #999; font-size: 14px; cursor: pointer; }
    .error-msg { color: #EE4D2D; font-size: 13px; margin-bottom: 10px; display: none; text-align: center; }
    .success-msg { color: #4CAF50; font-size: 13px; margin-bottom: 10px; display: none; text-align: center; }

    /* Painel Admin */
    .admin-panel {
      display: none;
      background: white;
      position: fixed;
      top: 0;
      right: 0;
      width: 100%;
      max-width: 420px;
      height: 100%;
      z-index: 400;
      overflow-y: auto;
      box-shadow: -2px 0 10px rgba(0,0,0,0.1);
    }

    .admin-panel.show { display: block; }
    .admin-header { background: #4CAF50; color: white; padding: 15px; display: flex; justify-content: space-between; align-items: center; }
    .admin-header h3 { font-size: 16px; }
    .close-admin { font-size: 24px; cursor: pointer; }
    .admin-content { padding: 20px; }
    .admin-content h4 { margin-bottom: 15px; color: #333; }
    .admin-content input { width: 100%; padding: 10px; margin-bottom: 12px; border: 1px solid #ddd; border-radius: 4px; font-size: 14px; }
    .save-btn { background: #4CAF50; color: white; border: none; font-weight: 600; cursor: pointer; padding: 10px; border-radius: 4px; width: 100%; margin-bottom: 10px; }
    .product-list { margin-top: 20px; }
    .product-item { padding: 10px; border-bottom: 1px solid #eee; display: flex; justify-content: space-between; align-items: center; }
    .delete-btn { background: #f44336; color: white; border: none; padding: 5px 10px; border-radius: 3px; font-size: 12px; cursor: pointer; }
    .empty-state { text-align: center; padding: 40px 20px; color: #999; font-size: 14px; grid-column: 1 / -1; }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <header>
    <div class="header-top">
      <div class="logo">🔥 Ofertas Relâmpago</div>
      <div id="headerAuthArea">
        <button class="login-header-btn" id="openLoginBtn" onclick="openAuthModal()">Entrar</button>
      </div>
    </div>
    <div class="search-bar">
      <span>🔍</span>
      <input type="text" id="searchInput" placeholder="Buscar ofertas...">
    </div>
  </header>

  <!-- Produtos -->
  <div class="section-title">⚡ Compre antes que acabe!</div>
  <div class="products-grid" id="productsContainer"></div>

  <!-- Modal da Imagem -->
  <div class="image-modal" id="imageModal">
    <span class="modal-close" onclick="closeModal()">&times;</span>
    <div class="modal-product-name" id="modalProductName"></div>
    <div class="modal-timer" id="modalTimer">⏰ 00:00</div>
    <img id="modalImage" src="" alt="Produto">
    <button class="modal-buy-btn" id="modalBuyBtn">🛒 Comprar Agora</button>
  </div>

  <!-- Tela de Login/Cadastro -->
  <div class="auth-modal" id="authModal">
    <div class="auth-box">
      <h3 id="authTitle">🔐 Entrar</h3>
      <div class="error-msg" id="authError"></div>
      <div class="success-msg" id="authSuccess"></div>
      
      <input type="email" id="authEmail" placeholder="Seu e-mail">
      <input type="password" id="authPassword" placeholder="Sua senha">
      
      <button class="auth-btn" id="authSubmitBtn" onclick="handleAuth()">Entrar</button>
      <div class="auth-switch" id="authSwitchText" onclick="toggleAuthMode()">Não tem conta? Clique aqui</div>
      <div class="close-auth" onclick="closeAuthModal()">Voltar</div>
    </div>
  </div>

  <!-- Painel Admin -->
  <div class="admin-panel" id="adminPanel">
    <div class="admin-header">
      <h3>⚙️ Painel Administrativo</h3>
      <span class="close-admin" onclick="closeAdminPanel()">&times;</span>
    </div>
    <div class="admin-content">
      <h4>Adicionar Novo Produto</h4>
      <input type="text" id="prodName" placeholder="Nome do produto">
      <input type="text" id="prodPrice" placeholder="Preço (ex: 89.90)">
      <input type="text" id="prodOriginalPrice" placeholder="Preço original (ex: 149.90)">
      <input type="text" id="prodImage" placeholder="Link da imagem">
      <input type="text" id="prodLink" placeholder="Link da Shopee (seu afiliado)">
      <input type="text" id="prodTime" placeholder="Tempo em minutos (ex: 15)">
      <button class="save-btn" onclick="saveProduct()">✅ Salvar Produto</button>
      
      <div class="product-list">
        <h4>📋 Meus Produtos</h4>
        <div id="adminProductList"></div>
      </div>
    </div>
  </div>

  <script>
    // ================= CONFIGURAÇÃO =================
    const ADMIN_DOMAIN = '@admin.com'; // 🔑 E-mail terminando assim = Admin
    
    let isRegisterMode = false;
    let activeTimers = {};
    let products = JSON.parse(localStorage.getItem('myProducts')) || [];
    let users = JSON.parse(localStorage.getItem('siteUsers')) || [];
    let currentUser = JSON.parse(localStorage.getItem('currentUser')) || null;

    // ================= VERIFICAR USUÁRIO LOGADO =================
    function updateHeaderAuthArea() {
      const area = document.getElementById('headerAuthArea');
      if (currentUser) {
        area.innerHTML = `
          <div class="user-info">
            <span>${currentUser.email.split('@')[0]}</span>
            <button class="logout-btn" onclick="logout()">Sair</button>
          </div>
        `;
        if (currentUser.isAdmin) {
          // Admin fica logado até clicar em Sair
        }
      } else {
        area.innerHTML = `<button class="login-header-btn" id="openLoginBtn" onclick="openAuthModal()">Entrar</button>`;
      }
    }

    function logout() {
      localStorage.removeItem('currentUser');
      currentUser = null;
      closeAdminPanel();
      updateHeaderAuthArea();
    }

    // ================= TELA DE LOGIN =================
    function openAuthModal() {
      document.getElementById('authModal').classList.add('show');
      document.getElementById('authEmail').value = '';
      document.getElementById('authPassword').value = '';
      document.getElementById('authError').style.display = 'none';
      document.getElementById('authSuccess').style.display = 'none';
      isRegisterMode = false;
      updateAuthMode();
    }

    function closeAuthModal() {
      document.getElementById('authModal').classList.remove('show');
    }

    function toggleAuthMode() {
      isRegisterMode = !isRegisterMode;
      updateAuthMode();
    }

    function updateAuthMode() {
      if (isRegisterMode) {
        document.getElementById('authTitle').textContent = '📝 Criar Conta';
        document.getElementById('authSubmitBtn').textContent = 'Criar Conta';
        document.getElementById('authSwitchText').textContent = 'Já tem conta? Entre aqui';
      } else {
        document.getElementById('authTitle').textContent = '🔐 Entrar';
        document.getElementById('authSubmitBtn').textContent = 'Entrar';
        document.getElementById('authSwitchText').textContent = 'Não tem conta? Clique aqui';
      }
      document.getElementById('authError').style.display = 'none';
      document.getElementById('authSuccess').style.display = 'none';
    }

    function showError(msg) {
      document.getElementById('authError').textContent = msg;
      document.getElementById('authError').style.display = 'block';
    }

    function showSuccess(msg) {
      document.getElementById('authSuccess').textContent = msg;
      document.getElementById('authSuccess').style.display = 'block';
    }

    function handleAuth() {
      const email = document.getElementById('authEmail').value.trim().toLowerCase();
      const password = document.getElementById('authPassword').value;

      if (!email || !password) {
        showError('Preencha todos os campos!');
        return;
      }

      // ✅ É Admin?
      if (email.endsWith(ADMIN_DOMAIN)) {
        let admin = users.find(u => u.email === email);
        if (!admin) {
          // Primeiro acesso - cria conta de admin
          if (password.length < 4) {
            showError('Use uma senha com pelo menos 4 caracteres');
            return;
          }
          admin = { email, password, isAdmin: true };
          users.push(admin);
          saveUsers();
          showSuccess('Conta administrativa criada! ✅');
          setTimeout(() => {
            currentUser = admin;
            saveCurrentUser();
            closeAuthModal();
            openAdminPanel();
            updateHeaderAuthArea();
          }, 800);
          return;
        }
        // Verifica senha do admin
        if (admin.password === password) {
          currentUser = admin;
          saveCurrentUser();
          closeAuthModal();
          openAdmin
          updateHeaderAuthArea();
          return;
        } else {
          showError('Senha incorreta!');
          return;
        }
      }

      // Usuário comum
      if (isRegisterMode) {
        // Criar nova conta
        if (users.find(u => u.email === email)) {
          showError('Este e-mail já está cadastrado!');
          return;
        }
        if (password.length < 4) {
          showError('Use pelo menos 4 caracteres na senha');
          return;
        }
        users.push({ email, password, isAdmin: false });
        saveUsers();
        showSuccess('Conta criada com sucesso! ✅');
        setTimeout(() => {
          currentUser = { email, isAdmin: false };
          saveCurrentUser();
          closeAuthModal();
          updateHeaderAuthArea();
        }, 800);
      } else {
        // Fazer login
        const user = users.find(u => u.email === email && u.password === password);
        if (!user) {
          showError('E-mail ou senha incorretos!');
          return;
        }
        currentUser = user;
        saveCurrentUser();
        closeAuthModal();
        updateHeaderAuthArea();
      }
    }

    function saveUsers() {
      localStorage.setItem('siteUsers', JSON.stringify(users));
    }

    function saveCurrentUser() {
      localStorage.setItem('currentUser', JSON.stringify(currentUser));
    }

    // ================= PAINEL ADMINISTRATIVO =================
    function openAdminPanel() {
      document.getElementById('adminPanel').classList.add('show');
      renderAdminProductList();
    }

    function closeAdminPanel() {
      document.getElementById('adminPanel').classList.remove('show');
      clearProductForm();
    }

    function clearProductForm() {
      document.getElementById('prodName').value = '';
      document.getElementById('prodPrice').value = '';
      document.getElementById('prodOriginalPrice').value = '';
      document.getElementById('prodImage').value = '';
      document.getElementById('prodLink').value = '';
      document.getElementById('prodTime').value = '';
    }

    function saveProduct() {
      const name = document.getElementById('prodName').value.trim();
      const price = parseFloat(document.getElementById('prodPrice').value);
      const originalPrice = parseFloat(document.getElementById('prodOriginalPrice').value) || price;
      const image = document.getElementById('prodImage').value.trim();
      const link = document.getElementById('prodLink').value.trim();
      const timeInMinutes = parseInt(document.getElementById('prodTime').value) || 15;

      if (!name || !price || !image || !link) {
        alert('⚠️ Preencha nome, preço, imagem e link!');
        return;
      }

      const discount = originalPrice > price ? Math.round((1 - price / originalPrice) * 100) : 0;

      const newProduct = {
        id: Date.now(),
        name,
        price,
        originalPrice,
        discount,
        image,
        link,
        timeInMinutes
      };

      products.unshift(newProduct);
      saveProducts();
      renderProducts(products);
      renderAdminProductList();
      clearProductForm();
      alert('✅ Produto cadastrado com sucesso!');
    }

    function deleteProduct(id) {
      if (confirm('❌ Excluir este produto?')) {
        products = products.filter(p => p.id !== id);
        saveProducts();
        renderProducts(products);
        renderAdminProductList();
      }
    }

    function saveProducts() {
      localStorage.setItem('myProducts', JSON.stringify(products));
    }

    function renderAdminProductList() {
      const list = document.getElementById('adminProductList');
      if (products.length === 0) {
        list.innerHTML = '<p style="color:#999; font-size:13px;">Nenhum produto cadastrado</p>';
        return;
      }
      list.innerHTML = products.map(p => `
        <div class="product-item">
          <div style="flex:1; font-size:13px;">
            <div style="color:#333;">${p.name.length > 28 ? p.name.substring(0, 28) + '...' : p.name}</div>
            <div style="color:#EE4D2D; font-weight:600;">R$ ${p.price.toFixed(2)}</div>
          </div>
          <button class="delete-btn" onclick="deleteProduct(${p.id})">Excluir</button>
        </div>
      `).join('');
    }

    // ================= MODAL DE IMAGEM E COMPRA =================
    let currentModalProduct = null;
    let modalTimerInterval = null;

    function openProductModal(product) {
      currentModalProduct = product;
      document.getElementById('modalImage').src = product.image;
      document.getElementById('modalProductName').textContent = product.name;
      document.getElementById('modalBuyBtn').onclick = () => {
        if (currentUser) {
          window.open(product.link, '_blank');
        } else {
          closeImageModal();
          openAuthModal();
        }
      };
      startModalTimer(product);
      document.getElementById('imageModal').classList.add('show');
    }

    function closeImageModal() {
      document.getElementById('imageModal').classList.remove('show');
      if (modalTimerInterval) clearInterval(modalTimerInterval);
    }

    function startModalTimer(product) {
      let endTime = parseInt(localStorage.getItem(`timer_${product.id}`));
      if (!endTime || new Date().getTime() > endTime) {
        endTime = new Date().getTime() + (product.timeInMinutes * 60 * 1000);
        localStorage.setItem(`timer_${product.id}`, endTime);
      }

      function updateModalTime() {
        const now = new Date().getTime();
        const distance = endTime - now;
        if (distance < 0) {
          document.getElementById('modalTimer').textContent = '⏰ TEMPO ESGOTADO!';
          clearInterval(modalTimerInterval);
          return;
        }
        const mins = Math.floor((distance % (1000 * 60)) / (1000 * 60));
        const secs = Math.floor((distance % (1000)) / 1000);
        document.getElementById('modalTimer').textContent = `⏰ ${String(mins).padStart(2, '0')}:${String(secs).padStart(2, '0')}`;
      }
      updateModalTime();
      modalTimerInterval = setInterval(updateModalTime, 1000);
    }

    // ================= CRONÔMETROS DOS PRODUTOS NA LISTA =================
    function startProductTimers() {
      products.forEach(product => {
        let endTime = parseInt(localStorage.getItem(`timer_${product.id}`));
        if (!endTime || new Date().getTime() > endTime) {
          endTime = new Date().getTime() + (product.timeInMinutes * 60 * 1000);
          localStorage.setItem(`timer_${product.id}`, endTime);
        }
      });
      
      setInterval(() => {
        products.forEach(product => {
          const endTime = parseInt(localStorage.getItem(`timer_${product.id}`));
          const now = new Date().getTime();
          const distance = endTime - now;
          const timerEl = document.getElementById(`prod-timer-${product.id}`);
          if (!timerEl) return;
          
          if (distance < 0) {
            timerEl.innerHTML = '<span class="time">ACABOU!</span>';
            return;
          }
          const mins = Math.floor((distance % (1000 * 60)) / (1000 * 60));
          const secs = Math.floor((distance % (1000)) / 1000);
          timerEl.innerHTML = `⏰ <span class="time">${String(mins).padStart(2, '0')}:${String(secs).padStart(2, '0')}</span> restantes`;
        });
      }, 1000);
    }

    // ================= RENDERIZAR PRODUTOS =================
    function renderProducts(productsToRender) {
      const container = document.getElementById('productsContainer');
      
      if (productsToRender.length === 0) {
        container.innerHTML = '<div class="empty-state">Nenhum produto encontrado 😕</div>';
        return;
      }
      
      container.innerHTML = productsToRender.map(product => `
        <div class="product-card">
          <img src="${product.image}" alt="${product.name}" class="product-image" 
               onclick='openProductModal(${JSON.stringify(product).replace(/'/g, "\\'")})' loading="lazy">
          <div class="product-info">
            <div class="product-name">${product.name}</div>
            <div>
              <span class="product-price">R$ ${product.price.toFixed(2)}</span>
              ${product.discount ? `<span class="product-discount">-${product.discount}%</span>` : ''}
            </div>
            <div class="product-timer" id="prod-timer-${product.id}">
              ⏰ <span class="time">${String(product.timeInMinutes).padStart(2, '0')}:00</span> restantes
            </div>
            <button class="buy-btn" onclick='openProductModal(${JSON.stringify(product).replace(/'/g, "\\'")})'>
              ${currentUser ? '🛒 Comprar Agora' : '🔐 Entrar para Comprar'}
            </button>
          </div>
        </div>
      `).join('');
    }

    // ================= BUSCA =================
    document.getElementById('searchInput').addEventListener('input', (e) => {
      const term = e.target.value.toLowerCase().trim();
      if (!term) {
        renderProducts(products);
        return;
      }
      const filtered = products.filter(p => p.name.toLowerCase().includes(term));
      renderProducts(filtered);
    });

    // ================= INICIALIZAR =================
    updateHeaderAuthArea();
    renderProducts(products);
    startProductTimers();
  </script>
</body>
</html>
