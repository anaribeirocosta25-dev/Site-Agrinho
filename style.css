/* ==========================================================================
   1. VARIÁVEIS DO DESIGN SYSTEM (:ROOT)
   ========================================================================== */
:root {
    /* Paleta de Cores (Padrão) */
    --primary-color: #d44179;
    --primary-light: #fbebf1;
    --secondary-color: #2c3e50;
    --bg-color: #faf7f8;
    --surface-color: #ffffff;
    --text-color: #333333;
    --text-light: #666666;
    
    /* Tipografia Básica (Base para alteração dinâmica) */
    --font-base-size: 16px;
    
    /* Espaçamentos e Bordas */
    --spacing-sm: 0.5rem;
    --spacing-md: 1rem;
    --spacing-lg: 2rem;
    --spacing-xl: 4rem;
    --radius: 8px;
    
    /* Transições */
    --transition-smooth: cubic-bezier(0.4, 0, 0.2, 1);
    --time-fast: 0.2s;
    --time-medium: 0.5s;
}

/* ==========================================================================
   2. MODO ALTO CONTRASTE (Acessibilidade)
   ========================================================================== */
body.high-contrast {
    --primary-color: #ffff00;
    --primary-light: #000000;
    --secondary-color: #ffffff;
    --bg-color: #000000;
    --surface-color: #121212;
    --text-color: #ffffff;
    --text-light: #dddddd;
}

body.high-contrast .btn-primary {
    color: #000000 !important;
    background-color: var(--primary-color) !important;
    border: 2px solid var(--primary-color);
}

body.high-contrast .accordion-header {
    border: 1px solid #ffffff;
}

/* ==========================================================================
   3. ESTILOS GERAIS E RESET
   ========================================================================== */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    font-size: var(--font-base-size);
    scroll-behavior: smooth;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
}

body {
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
    transition: background-color var(--time-fast), color var(--time-fast);
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

/* Foco Visível para Navegação por Teclado */
*:focus-visible {
    outline: 3px solid var(--primary-color);
    outline-offset: 3px;
}

/* ==========================================================================
   4. BARRA DE ACESSIBILIDADE
   ========================================================================== */
.accessibility-bar {
    background-color: var(--secondary-color);
    padding: var(--spacing-sm) 5%;
    display: flex;
    justify-content: flex-end;
    gap: var(--spacing-md);
}

.accessibility-bar button {
    background: transparent;
    color: #ffffff;
    border: 1px solid rgba(255, 255, 255, 0.4);
    padding: 0.3rem 0.8rem;
    cursor: pointer;
    border-radius: var(--radius);
    font-size: 0.85rem;
}

/* ==========================================================================
   5. HEADER & NAVEGAÇÃO
   ========================================================================== */
.main-header {
    background-color: var(--surface-color);
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 100;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: var(--spacing-md) 5%;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: var(--primary-color);
    text-decoration: none;
}

.nav-menu {
    display: flex;
    gap: var(--spacing-lg);
    list-style: none;
}

.nav-menu a {
    color: var(--text-color);
    text-decoration: none;
    font-weight: 500;
}

/* ==========================================================================
   6. HERO SECTION (Layout Flex)
   ========================================================================== */
.hero-section {
    background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1525310072745-f49212b5ac6d?q=80&w=1200') no-repeat center center/cover;
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #ffffff;
    padding: var(--spacing-xl) var(--spacing-md);
}

.hero-content h1 {
    font-size: 2.5rem;
    margin-bottom: var(--spacing-md);
}

.hero-content p {
    font-size: 1.2rem;
    max-width: 600px;
    margin: 0 auto var(--spacing-lg);
}

.btn-primary {
    display: inline-block;
    background-color: var(--primary-color);
    color: white;
    padding: 0.8rem 2rem;
    text-decoration: none;
    border-radius: var(--radius);
    font-weight: bold;
    transition: transform var(--time-fast);
}

.btn-primary:hover {
    transform: translateY(-2px);
}

/* ==========================================================================
   7. SEÇÃO SOBRE (Layout Grid - Edite aqui a estrutura de colunas)
   ========================================================================== */
.about-section {
    padding: var(--spacing-xl) 0;
}

.about-section h2 {
    text-align: center;
    margin-bottom: var(--spacing-xl);
}

/* GRID CONFIGURATION: Modifique as colunas aqui para Desktop */
.about-grid {
    display: grid;
    grid-template-columns: 1fr; /* Mobile-First: 1 Coluna */
    gap: var(--spacing-lg);
}

.about-card {
    background-color: var(--surface-color);
    padding: var(--spacing-lg);
    border-radius: var(--radius);
    box-shadow: 0 4px 6px rgba(0,0,0,0.02);
    border-left: 5px solid var(--primary-color);
}

/* ==========================================================================
   8. COMPONENTE: CARROSSEL (Galeria)
   ========================================================================== */
.gallery-section {
    background-color: var(--primary-light);
    padding: var(--spacing-xl) 0;
}

.gallery-section h2, .section-subtitle {
    text-align: center;
}
.section-subtitle { margin-bottom: var(--spacing-xl); color: var(--text-light); }

.carousel-container {
    position: relative;
    max-width: 600px;
    margin: 0 auto;
    overflow: hidden;
}

.carousel-track-container {
    overflow: hidden;
    width: 100%;
}

.carousel-track {
    display: flex;
    list-style: none;
    transition: transform var(--time-medium) var(--transition-smooth);
}

.carousel-slide {
    min-width: 100%;
    box-sizing: border-box;
    padding: var(--spacing-md);
}

.card-item {
    background: var(--surface-color);
    border-radius: var(--radius);
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.card-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.card-content {
    padding: var(--spacing-lg);
}

.carousel-controls {
    display: flex;
    justify-content: space-between;
    position: absolute;
    top: 50%;
    width: 100%;
    transform: translateY(-50%);
    pointer-events: none;
}

.carousel-btn {
    background: var(--secondary-color);
    color: #ffffff;
    border: none;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    cursor: pointer;
    pointer-events: auto;
    display: flex;
    align-items: center;
    justify-content: center;
}

/* ==========================================================================
   9. COMPONENTE: ACORDEÃO (FAQ)
   ========================================================================== */
.faq-section {
    padding: var(--spacing-xl) 0;
}

.faq-section h2 {
    text-align: center;
    margin-bottom: var(--spacing-xl);
}

.accordion-item {
    background-color: var(--surface-color);
    margin-bottom: var(--spacing-md);
    border-radius: var(--radius);
    overflow: hidden;
}

.accordion-header {
    width: 100%;
    background: none;
    border: none;
    text-align: left;
    padding: var(--spacing-lg);
    font-size: 1.1rem;
    font-weight: 600;
    color: var(--text-color);
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.accordion-icon {
    transition: transform var(--time-fast);
}

.accordion-header[aria-expanded="true"] .accordion-icon {
    transform: rotate(180deg);
}

.accordion-panel {
    max-height: 0;
    overflow: hidden;
    transition: max-height var(--time-medium) var(--transition-smooth);
}

.accordion-content {
    padding: 0 var(--spacing-lg) var(--spacing-lg) var(--spacing-lg);
    color: var(--text-light);
}

/* ==========================================================================
   10. FOOTER & ANIMAÇÃO DE REVEAL
   ========================================================================== */
.main-footer {
    background-color: var(--secondary-color);
    color: #ffffff;
    text-align: center;
    padding: var(--spacing-lg) 0;
    font-size: 0.9rem;
}

/* Efeito de Scroll Reveal */
.scroll-reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s ease, transform 0.8s ease;
}

.scroll-reveal.active {
    opacity: 1;
    transform: translateY(0);
}

/* ==========================================================================
   11. MEDIA QUERIES (Responsividade)
   ========================================================================== */
@media (min-width: 768px) {
    /* Ajuste de Grid para telas maiores */
    .about-grid {
        grid-template-columns: repeat(2, 1fr);
    }
    
    .hero-content h1 {
        font-size: 3.5rem;
    }
}
