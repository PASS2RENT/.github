<div align="center">

![PASS2RENT](https://raw.githubusercontent.com/PASS2RENT/.github/main/profile/pass2rent-h-logo.svg?raw=true)

<br/>
PASS2RENT is an innovative contactless car rental solution with 24/7 pick-up
<br/>

### [Know more...](https://pass2rent.com/)

</div>

**Smart Booking & Rental Management Platform — Web Components, API & Full Integrations**


### 🔄 GitHub Actions (CI/CD)

> Replace the workflow filenames if your repo uses different ones.
> These badges will automatically reflect build/test/deploy status.

**pass2rent-lit-webcomponents:**

![Build](https://github.com/PASS2RENT/pass2rent-lit-webcomponents/actions/workflows/build.yml/badge.svg)
![Tests](https://github.com/PASS2RENT/pass2rent-lit-webcomponents/actions/workflows/tests.yml/badge.svg)
![Publish](https://github.com/PASS2RENT/pass2rent-lit-webcomponents/actions/workflows/publish.yml/badge.svg)

---

## 🚀 What is PASS2RENT?

**PASS2RENT is a modern platform for integrating booking and rental systems into any website or application.**

Our mission is to provide developers, partners, and businesses with **plug-and-play Web Components, APIs, and tools** to manage:

* Real-time availability
* Dynamic pricing & seasonal rules
* Booking & customer flow
* Payments (via Stripe)
* EU VAT validation
* Multilingual interfaces
* Maps & address autocomplete (via Mapbox)

Whether you run **car rentals, equipment rentals, accommodation, or any booking-based service**, PASS2RENT makes integration effortless.

---

## 🌟 Why Choose PASS2RENT?

### ✔ Framework-Agnostic Components

Our **Lit-based Web Components** work everywhere:
HTML • WordPress • React • Vue • Svelte • Angular • Webflow • Next.js • Nuxt • etc.

### ✔ Minimal Integration

Add a `<script>` tag or install an npm package — and your website instantly has a full booking UI.

### ✔ API-Driven Flexibility

Use our backend API to build custom booking experiences, real-time availability, pricing queries, or custom workflows.

### ✔ Built-In Localization (i18n)

Powered by Lit’s official localization engine.

### ✔ Payment Ready

Turnkey Stripe Elements integration.

### ✔ EU-Ready

VAT validation through VIES SOAP/REST endpoints.

---

## 📦 Main Repositories & Packages

| Repo / Package                       | Description                                       |
| ------------------------------------ | ------------------------------------------------- |
| **pass2rent-lit-webcomponents**      | Web Components for embedding PASS2RENT booking UI |
| *(More packages may be listed here)* | Backend APIs, utilities, docs, and integrations   |

📌 Main repo: [https://github.com/PASS2RENT/pass2rent-lit-webcomponents](https://github.com/PASS2RENT/pass2rent-lit-webcomponents)

---

## 🧩 Built-in Integrations & External Services

### **Localization (Lit i18n)**

[https://lit.dev/docs/localization/overview/](https://lit.dev/docs/localization/overview/)

### **Stripe Payments**

* [https://github.com/bennypowers/stripe-elements](https://github.com/bennypowers/stripe-elements)
* [https://docs.stripe.com/js](https://docs.stripe.com/js)

### **Mapbox Search / Autocomplete**

* [https://docs.mapbox.com/mapbox-search-js/guides/](https://docs.mapbox.com/mapbox-search-js/guides/)
* [https://docs.mapbox.com/mapbox-search-js/guides/search/web/](https://docs.mapbox.com/mapbox-search-js/guides/search/web/)

### **EU VAT Validation (VIES)**

* [https://ec.europa.eu/taxation_customs/vies/](https://ec.europa.eu/taxation_customs/vies/)
* REST example:
  `https://ec.europa.eu/taxation_customs/vies/rest-api/ms/LT/vat/LT100005451818`

**SOAP Example (UAB ODIFIS):**

```xml
<env:Envelope xmlns:env="http://schemas.xmlsoap.org/soap/envelope/">
  <env:Header/>
  <env:Body>
    <ns2:checkVatResponse 
      xmlns:ns2="urn:ec.europa.eu:taxud:vies:services:checkVat:types">
      <ns2:countryCode>LT</ns2:countryCode>
      <ns2:vatNumber>100005451818</ns2:vatNumber>
      <ns2:requestDate>2024-11-18+01:00</ns2:requestDate>
      <ns2:valid>true</ns2:valid>
      <ns2:name>UAB "ODIFIS"</ns2:name>
      <ns2:address>
        Ausros g. 56-3, LT-28147 Utena
      </ns2:address>
    </ns2:checkVatResponse>
  </env:Body>
</env:Envelope>
```

---

## 🛠️ Developer Resources

* API optimization for Web Components:
  [https://dev.to/collinkleest/optimizing-api-calls-in-web-components-14kn](https://dev.to/collinkleest/optimizing-api-calls-in-web-components-14kn)
* Publish an npm package:
  [https://www.freecodecamp.org/news/how-to-create-and-publish-your-first-npm-package/](https://www.freecodecamp.org/news/how-to-create-and-publish-your-first-npm-package/)

---

## 🧠 Benefits for Your Business

PASS2RENT eliminates complexity and enables:

* Fast deployment
* Lower development costs
* EU tax compliance
* Multi-language customer experience
* Secure payments
* Reliable availability & pricing logic
* A unified booking experience across partner websites

---

## 🤝 Collaboration & Contributions

We welcome:

* Bug fixes
* New integrations
* Translations
* Feature ideas
* Documentation improvements

Join us in building the most flexible booking platform ecosystem.

---

## 🔎 SEO Keywords

`booking system`, `rental software`, `car rental`, `equipment rental`,
`web components`, `lit`, `booking widget`, `custom elements`,
`availability`, `pricing`, `stripe`, `mapbox`,
`VAT`, `EU VIES`, `i18n`, `localization`,
`javascript`, `typescript`, `API`, `plugin`, `checkout`, `widget`

---

## 🌐 Learn More

👉 Web Components package:
[https://github.com/PASS2RENT/pass2rent-lit-webcomponents](https://github.com/PASS2RENT/pass2rent-lit-webcomponents)

