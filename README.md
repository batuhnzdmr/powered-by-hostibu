# Powered by HOSTIBU

A lightweight snippet developed and maintained by **Hostibu**, this component allows you to easily add a "Powered by Hostibu" badge to your website. Fully responsive and easy to integrate, it's perfect for showcasing your hosting provider while maintaining a clean design.

---

## 🧩 Features

- Simple HTML & CSS integration
- Responsive and modern layout
- SEO-friendly and brand-visible
- Open-source and free to use

---

## 🔧 Installation

1. Add the following HTML code to the bottom of your website.

```html
<!-- HOSTIBU -->
<div id="hostibu">
    <a href="https://hostibu.com" target="_blank">
        <img src="/assets/img/powered-by-hostibu.svg" alt="Hosted by Hostibu.">
    </a>
</div>
```

> [!NOTE]
> Either in the footer section or just before the closing </body> tag (if your site doesn't have a footer

2. Then include this CSS in your stylesheet:

```css
/** HOSTIBU **/
#hostibu {
    z-index: 99999;
    display: flex;
    margin-top: 2rem;
    padding-bottom: 2rem;
    justify-content: center;
}

#hostibu img {
    height: 3rem;
    border: none !important;
}

@media (min-width: 1200px) {
    #hostibu {
        justify-content: flex-start;
        padding-left: 5rem;
    }
}
```

3. Finally, upload the image file to the ``/assets/img/powered-by-hostibu.svg`` directory.

> [!NOTE]
> You can also upload it to a different location by adjusting the HTML code accordingly.

> [!TIP]
> [Click here](src/assets/img/powered-by-hostibu.svg) to install image.

---

## 💡 Example Usage

You can find an example usage inside the [src](src/) folder.  
Feel free to modify and adapt the design to fit your website’s layout and theme.

---

## 🧪 Live Demo
[Gölbaşı Platform](https://golbasiplatform.com)

---

## 📂 Project Structure

```
html/
├── assets/
│   └── css/
│       └── custom.css
│   └── img/
│       └── powered-by-hostibu.svg
├── index.html
```

---

## 🛡️ License

This project is licensed under the [MIT](LICENSE) License.

---

## 💼 Powered by [Hostibu](https://hostibu.com)

> This project is proudly powered by **Hostibu**. Show your support by displaying the badge on your site.

## ❤️ Made by [batuhnzdmr](https://github.com/batuhnzdmr)
> This project made by Batuhan Özdemir.
> Website: https://batuhnzdmr.me
