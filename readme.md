# usexmr.com — Official Website with Flyer

Welcome to the official repository for [usexmr.com](https://usexmr.com), a Monero Community Project. This website provides educational resources, guides, and a flyer to help users understand and use Monero for private, secure, and decentralized transactions.

## About

**usexmr.com** is a non-commercial, community-driven project. Our goal is to make Monero accessible to everyone by providing clear, multilingual information and easy-to-use resources.

## Languages

The flyer and website are available in following languages:

- English
- 中文
- Español
- Русский
- Português
- Português Brasileiro
- Français
- Deutsch
- Polski
- Türkçe
- Nederlands
- Italiano
- فارسی
- Slovak
- Română
- Valencià
- Papiamento
- Kriolu
- Հայերեն
- Esperanto

Simply use the language switcher at the top of [usexmr.com](https://usexmr.com).

## Contributing

We welcome contributions from the Monero community! The easiest way to help is by translating the website into your language.

### How to Translate

1. **Fork this repository:**  
   Just [fork it](https://github.com/schmidt1024/monero-flyer/fork) or use the botton "Fork" above.

2. **Copy the English translation file:**  
   Go to [`i18n/en/en.json`](i18n/en/en.json) and copy its contents.

3. **Create a new language folder:**  
   Inside the [`i18n`](i18n/) directory, create a new folder named after your language code (e.g., `fr` for French, `es` for Spanish).

4. **Add your translation:**  
   Paste the copied `en.json` into your new folder and rename it to match your language code (e.g., `fr.json`).  
   Example: `i18n/fr/fr.json`

5. **Translate all values:**  
   Replace the English text with your translation.  
   **Do not change the keys.**

   In the JSON file you will find the following two sections:

   **"pdf": {...}** <- all keys here are for the flyer

   **"website": {...}** <- all keys here are for the website

6. **Submit a Pull Request:**  
   Commit your changes and open a pull request. Please mention your language in the PR title.

Once your pull request is submitted, we will review your translation. If everything looks good, we will generate PDF flyers in both light and dark modes based on your translation. Preview images and the PDFs will be added to your PR before it is merged.

**Alternative:**  
If you prefer, you can simply take the JSON file, translate it, and reach out directly to [@schmidt1024 on X (Twitter)](https://x.com/schmidt1024). We will help you get your translation added and generate the flyers for you.

## License

This project is open source and available under the GFY License.

---

Thank you for supporting Monero and helping make privacy accessible to all!
