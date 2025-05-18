
# 📬 Contact Us Form

A responsive and elegant **Contact Us** form built using **HTML** and **CSS**, powered by **Formspree** for backend form handling. Fully functional with a clean design, it's mobile-friendly and ready to integrate into any website.

## ✨ Features

* Modern design with **Poppins** font
* Fully responsive layout
* Smooth hover and active button effects
* Clean form validation using HTML5
* Easily customizable and embeddable
* Uses **Formspree** for form submission (no backend required)

## 📸 Screenshot

![Contact Form Screenshot](./images/contact-screenshot.png) 

## 📂 File Structure

```
📁 contact-form
├── index.html
├── images/
│   └── contact-screenshot.png (optional)
└── README.md
```

## 🛠️ How to Use

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/contact-form.git
```

2. **Open the HTML file in your browser:**

```bash
cd contact-form
open index.html
```

3. **Customize as needed:**

   * Replace the Formspree endpoint (`https://formspree.io/f/mrbqjvor`) with your own Formspree link.
   * Modify colors, labels, or fonts if required.

## 📧 Backend Integration

This form uses **Formspree**:

* Go to [Formspree.io](https://formspree.io)
* Create an account
* Generate a form endpoint
* Replace the `action` URL in the HTML:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🧪 Validation

* All fields are required (`required` attribute in HTML)
* Email input uses HTML5 validation

## 🧱 Built With

* HTML5
* CSS3
* Google Fonts (Poppins)
* [Formspree](https://formspree.io) for handling submissions

## 📋 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like badges, deploy instructions (e.g., GitHub Pages), or want to convert this into a React/Vue component!
