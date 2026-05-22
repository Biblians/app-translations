# Biblians App Translations

This repository contains the translation files for the Biblians app.  
The goal is simple. With the help of native speakers we want to make Biblians usable and natural in as many languages as possible.[web:0]

## Languages

Currently included

- English (en)
- Spanish (es)
- French (fr)
- Portuguese European (pt)
- Portuguese Brazilian (pt-BR)
- Russian (ru)

If you are a native or very fluent speaker of any of these, your help is welcome.[conversation_history:0]

## Folder structure

All translation files live in the `locales` folder

- `locales/app_en.arb`
- `locales/app_es.arb`
- `locales/app_fr.arb`
- `locales/app_pt.arb`
- `locales/app_pt_BR.arb`
- `locales/app_ru.arb`

Each file is an ARB file, which is a JSON based format used for application resources.[web:10]  
The English file `locales/app_en.arb` is the main reference for meaning and context, so please always compare your language with that file while translating.

## How to contribute

1. Fork this repo  
   Click “Fork” on GitHub and clone your fork locally.[web:12]

2. Check the English file for context  
   Open `locales/app_en.arb` to understand what each key means, then open the file for your language in the same folder.

3. Edit the ARB file for your language  
   - Only change the values, not the keys  
   - Keep placeholders such as `{name}` and `{count}` exactly as they are  
   - Do not change metadata entries that start with `@`, for example `@someKey`  
   - Aim for clear, natural language instead of word for word translation[web:10]  

4. Check the ARB file is valid  
   - Make sure there are no missing commas or quotes  
   - Use any JSON or ARB aware editor or an online validator if needed[web:9]  

5. Create a Pull Request  
   - Commit your changes with a clear message, for example  
     `git commit -m "Improve Spanish translations for settings"`  
   - Open a Pull Request and describe  
     - Language  
     - What you changed, such as new translations, fixes or improvements  

## Style guidelines

- Keep the tone warm, respectful and friendly, fitting a Bible chat and study app[web:0]  
- Prefer terms commonly used in trusted Bible translations in your language  
- Keep short UI labels, such as buttons and menu items, as concise as possible  
- For texts related to personal reflections or confessions, use gentle and non judgmental wording[web:0]  

## Reporting issues

If you notice a problem in any language

- Open a GitHub issue and include  
  - Language  
  - The key or a short description of where it appears  
  - The current text  
  - Your suggested correction  

## Links and contact

- Website https://biblians.com/[web:0]  
- Google Play https://play.google.com/store/apps/details?id=com.biblians.app[web:0]  
- Email support@biblians.com  

Thank you for helping more people read, chat about and study the Bible in their own language with Biblians.[web:0]