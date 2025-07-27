# Samsung Store Carousel

## Overview

The **Samsung Store Carousel** is a modern, interactive web application showcasing a product carousel for Samsung's premium devices, including the **Galaxy S24 Ultra**, **Galaxy A55**, and **Galaxy Fridge**. Built with **HTML5**, **CSS3**, and **JavaScript**, this project demonstrates proficiency in **front-end development**, **responsive design**, and **user experience (UX)** principles.  

The carousel features:  
- **Automatic sliding**  
- **Manual navigation**  
- **Clickable call-to-action (CTA) buttons** that link to official Samsung product pages  
- Styled with a futuristic **neon aesthetic**  

---

### ✅ Key Features
- **Interactive Carousel**: Smooth transitions between three products using **CSS animations** and **JavaScript** for both automatic (every 5 seconds) and manual navigation (via arrow buttons).  
- **Responsive Design**: Optimized layout for various screen sizes, ensuring a seamless experience on desktop and mobile devices.  
- **Semantic HTML**: Structured with **HTML5** best practices for **accessibility** and **SEO**.  
- **Neon Aesthetic**: Custom **CSS3** styling with gradients, shadows, and animations to create a futuristic look inspired by Samsung's brand.  
- **Clickable CTAs**: "Saiba mais" buttons implemented as `<a>` elements, linking to external Samsung product pages with **target="_blank"** behavior.  
- **Dynamic Indicators**: Number and dot indicators sync with the carousel's active item, enhancing **user feedback**.  
- **Cross-Browser Compatibility**: Tested to ensure consistent performance across modern browsers (Chrome, Firefox, Edge).  

---

### 🛠 Technologies Used
- **HTML5**: For semantic structure and accessibility.  
- **CSS3**: For styling, animations, and responsive layout (flexbox, transforms, gradients, box-shadow).  
- **JavaScript**: For carousel logic, DOM manipulation, and event handling.  
- **Google Fonts**: Montserrat and Orbitron fonts for typography.  
- **Git**: Version control for project management.  

---

### ▶ How to Clone and Run
Follow these steps to clone and run the project locally:

**1. Clone the Repository**:
```bash
git clone https://github.com/RamonVeirone/samsung-store-carousel.git
```

**2. Navigate to the Project Directory**:
```bash
cd samsung-store-carousel
```

**3. Open the Application**:
- **Option 1:** Open `index.html` directly in a modern web browser (Chrome, Firefox, Edge).  
- **Option 2:** Use a local server for a better development experience:  
    - Install the **Live Server** extension in **Visual Studio Code**.  
    - Right-click `index.html` and select **"Open with Live Server"**.  

**4. Explore the Carousel**:
- Use the left and right arrow buttons to navigate manually.  
- Wait 5 seconds to observe automatic sliding.  
- Click the **"Saiba mais"** buttons to visit Samsung product pages in new tabs.  

---

### 📂 Project Structure
```
samsung-store-carousel/
├── img/
│   ├── galaxy24-img.png
│   ├── galaxy55-img.png
│   └── fridge-img.png
├── index.html
├── styles.css
├── scripts.js
└── README.md
```

**Description**:  
- `img/`: Contains product images for the carousel.  
- `index.html`: Main HTML file with semantic structure.  
- `styles.css`: CSS file with neon styling, animations, and responsive design.  
- `scripts.js`: JavaScript file for carousel functionality and event handling.  

---

### ⚠ Challenges and Solutions
- **Challenge:** Ensuring **"Saiba mais"** buttons were clickable.  
  **Solution:** Replaced `<button>` with `<a>` for semantic correctness, adjusted **z-index hierarchy (1 to 5)**, and used `display: none` for inactive carousel items to prevent click blocking.  

- **Challenge:** Preventing inactive carousel items from interfering with interactions.  
  **Solution:** Applied `display: none` to `.item` and `display: flex` to `.active`, ensuring only the active item is interactive.  

- **Challenge:** Maintaining a futuristic aesthetic.  
  **Solution:** Used **CSS gradients**, **box-shadows**, and **Orbitron font** to create a neon, Samsung-inspired design.  

---

### 💡 How to Use
- **Navigation:**  
    - Click the left (`#prev`) or right (`#next`) arrow buttons to cycle through products.  
    - The carousel automatically advances every 5 seconds.  

- **Indicators:**  
    - The number indicator (e.g., "01", "02", "03") and dots sync with the active product.  

- **Call-to-Action:**  
    - Click **"Saiba mais"** buttons to open official Samsung product pages in new tabs.  

- **Menu Links:**  
    - Use the header navigation (Home, About, Contact) to visit external links.  

---

### 🧩 Development Notes
- **Version Control:** The project uses **Git** with atomic commits following conventional commit guidelines (e.g., `fix: Enable Saiba mais button clicks`).  
- **Code Quality:** Formatted with **Prettier** for consistency and readability.  
- **Testing:** Validated across Chrome, Firefox, and Edge for cross-browser compatibility.  

---

### 🚀 Future Improvements
- Adding **pause/resume functionality** for the carousel on hover.  
- Implementing **touch gestures** for mobile navigation.  
- Enhancing **accessibility with ARIA attributes**.  

---

### 📞 Contact
For feedback or questions, reach out via **[GitHub](https://github.com/RamonVeirone)** or the contact link in the application.  

---

## 🇧🇷 Carrossel da Samsung Store

### Visão Geral
O **Carrossel da Samsung Store** é uma aplicação web moderna e interativa que apresenta um carrossel de produtos premium da Samsung, incluindo o **Galaxy S24 Ultra**, **Galaxy A55** e **Galaxy Fridge**. Desenvolvido com **HTML5**, **CSS3** e **JavaScript**, este projeto demonstra competência em **desenvolvimento front-end**, **design responsivo** e princípios de **experiência do usuário (UX)**.  

O carrossel possui:  
- **Navegação automática**  
- **Navegação manual**  
- **Botões de chamada para ação (CTA) clicáveis** que levam às páginas oficiais dos produtos Samsung  
- Estilização com uma estética **neon futurista**  

---

### ✅ Principais Funcionalidades
- **Carrossel Interativo:** Transições suaves entre três produtos usando animações CSS e JavaScript para navegação automática (a cada 5 segundos) e manual (via botões de setas).  
- **Design Responsivo:** Layout otimizado para diferentes tamanhos de tela, garantindo uma experiência fluida em dispositivos desktop e móveis.  
- **HTML Semântico:** Estruturado com boas práticas de HTML5 para acessibilidade e SEO.  
- **Estética Neon:** Estilização personalizada com CSS3, incluindo gradientes, sombras e animações para um visual futurista inspirado na marca Samsung.  
- **CTAs Clicáveis:** Botões **"Saiba mais"** implementados como elementos `<a>`, vinculados a páginas de produtos Samsung com comportamento **target="_blank"**.  
- **Indicadores Dinâmicos:** Indicadores numéricos e de pontos sincronizam com o item ativo do carrossel.  
- **Compatibilidade Cross-Browser:** Testado para desempenho consistente em navegadores modernos (Chrome, Firefox, Edge).  

---

### 🛠 Tecnologias Utilizadas
- **HTML5**, **CSS3**, **JavaScript**  
- **Google Fonts** (Montserrat e Orbitron)  
- **Git** para controle de versão  

---

### ▶ Como Clonar e Executar
```bash
git clone https://github.com/RamonVeirone/samsung-store-carousel.git
cd samsung-store-carousel
```

**Opções para abrir a aplicação:**  
- **Opção 1:** Abra `index.html` diretamente no navegador.  
- **Opção 2:** Use **Live Server** no VS Code para melhor experiência.  

---

### 📂 Estrutura do Projeto
*(mesma estrutura apresentada acima)*  

---

### ⚠ Desafios e Soluções
*(mesmos pontos da seção em inglês)*  

---

### 💡 Como Usar
*(mesmos pontos da seção em inglês)*  

---

### 🚀 Melhorias Futuras
*(mesmos pontos da seção em inglês)*  

---
