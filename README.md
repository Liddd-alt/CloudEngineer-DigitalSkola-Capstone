# 🚀 CloudEngineer-DigitalSkola-Capstone

Project akhir (Capstone) program Digital Skola Cloud Engineer berupa aplikasi Web (Fashion Studio) yang di-deploy secara otomatis ke **Azure App Service (Linux)** menggunakan **GitHub Actions** dengan sistem autentikasi **OIDC (OpenID Connect)**.

```markdown
# 🚀 CloudEngineer-DigitalSkola-Capstone

Project akhir (Capstone) program Digital Skola Cloud Engineer berupa aplikasi Web (Fashion Studio) yang di-deploy secara otomatis ke **Azure App Service (Linux)** menggunakan **GitHub Actions** dengan sistem autentikasi **OIDC (OpenID Connect)**.

```

---

## 🛠️ Tech Stack & Architecture (Capstone Deployment)

* **Cloud Provider:** Microsoft Azure (Region: `indonesiacentral`)
* **Hosting Service:** Azure App Service (App Service Plan: Free Tier F1)
* **Runtime:** Node.js / Vite
* **CI/CD Pipeline:** GitHub Actions
* **Authentication:** Azure Managed Identity dengan Federated Credentials (OIDC)

---

## 📋 Kriteria Teknis & Implementasi

| Aspek | Status | Keterangan Implementasi |
| --- | --- | --- |
| **CI/CD** | ✅ **Done** | Otomatisasi pipeline mencakup build, test, dan deploy via GitHub Actions setiap kali ada push ke branch `main`. |
| **Deployment** | ✅ **Done** | Berhasil deploy ke Azure App Service di region `indonesiacentral` menggunakan Linux environment. |
| **Keamanan** | ✅ **Done** | Menggunakan OIDC (tanpa hardcoded secrets atau password statis di repository) dan hak akses dibatasi menggunakan Azure IAM (Website Contributor). |
| **Monitoring** | ✅ **Done** | Menggunakan built-in Azure App Service Metrics & Logs (memantau CPU, Memory, Data In/Out, dan HTTP Status). |
| **Scaling** | ✅ **Optional** | Konfigurasi dasar di Free Tier (`indonesiacentral`) dengan opsi manual/auto-scale via App Service Plan. |
| **Dokumentasi** | ✅ **Done** | File `README.md` komprehensif di repository GitHub. |

---

## 🌐 Live Application URL

Aplikasi dapat diakses secara publik melalui tautan Azure Web App berikut:
👉 **[https://casptone-digitalskola-khalid-e6ghfwb0gqa0cxhv.indonesiacentral-01.azurewebsites.net](https://casptone-digitalskola-khalid-e6ghfwb0gqa0cxhv.indonesiacentral-01.azurewebsites.net)**

---

---

# Original App Documentation: Wibe Studio (React JS)

> **Note:** Below is the original documentation of the application template used for this capstone project.

# 🔥Build a Stunning Fashion Studio Website with React JS [ Locomotive Scroll + GSAP + Framer Motion ]

This repository contains final code for Fashion Studio Website in ReactJS.



View Demo👇:
https://wibe-studio.netlify.app/

### Run Locally (Development)
```bash
bun install
bun run dev      # start dev server at http://localhost:3000
bun run build    # production build to ./build
bun run preview  # preview the production build
```

### External Libraries used in this project:

[styled-components](https://styled-components.com/docs/advanced)

[GSAP](https://greensock.com/gsap/)

[Framer-Motion](https://www.framer.com/motion/)

[React-Locomotive-Scroll](https://www.npmjs.com/package/react-locomotive-scroll)

[Locomotive-Scroll](https://www.npmjs.com/package/locomotive-scroll)

#-------------------------------------------------------------------------------------------------------------------------------------

# 🔥Build a Stunning Fashion Studio Website with React JS [ Locomotive Scroll + GSAP + Framer Motion ]

![GitHub stars](https://img.shields.io/github/stars/codebucks27/wibe-studio-starter-files?style=social&logo=ApacheSpark&label=Stars)&nbsp;&nbsp;
![GitHub forks](https://img.shields.io/github/forks/codebucks27/wibe-studio-starter-files?style=social&logo=KashFlow&&label=Forks)&nbsp;&nbsp;
![Github Followers](https://img.shields.io/github/followers/codebucks27.svg?style=social&label=Follow)&nbsp;&nbsp;<br />

This repository contains final code for Fashion Studio Website in ReactJS. <br />

View Demo👇: <br />
https://wibe-studio.netlify.app/ <br />

checkout following **Tutorial** to learn👇: <br />
<a href="https://devdreaming.com/videos/build-stunning-fashion-studio-website-with-reactJS-locomotive-scroll-gsap" target="_blank">🔥Build a Stunning Fashion Studio Website with React JS</a> ![YouTube Video Views](https://img.shields.io/youtube/views/Ra1Fsa9YJCk?style=social) </br >

[![YouTube Video Views](https://img.shields.io/youtube/views/Ra1Fsa9YJCk?style=social)](https://youtu.be/Ra1Fsa9YJCk)<br />

## 🚀 2026 Refresh — What Changed

The original tutorial code (Create React App + React 17) has been modernized:

- **Build tool:** Migrated from `create-react-app` (`react-scripts`) to **Vite** for instant startup and fast HMR.
- **Package manager:** Switched to **bun**.
- **React:** `17.x` → `19.x` (uses the new `createRoot` API).
- **Routing:** `react-router-dom` `6.x` → `7.x`.
- **Animation:** `framer-motion` `6.x` → `12.x` (replaced removed `yoyo` with `repeat`/`repeatType`).
- **Styling:** `styled-components` `5.x` → `6.x` (custom DOM props converted to transient `$` props).
- **Fonts:** `@fontsource/*` `4.x` → `5.x`.
- Removed CRA-only files (`reportWebVitals`, `setupTests`, `manifest.json`, default logos, test boilerplate).

> Looking for the original tutorial code? Check out the pre-update commit: [`f256a87`](https://github.com/codebucks27/wibe-studio/commit/f256a8761be47c632f1f77ed4add04c10e91f0e6).

### Run Locally

```bash
bun install
bun run dev      # start dev server at http://localhost:3000
bun run build    # production build to ./build
bun run preview  # preview the production build
```



### Images of The Fashion Studio Website:
![HOME](https://github.com/codebucks27/wibe-studio-starter-files/blob/main/Wibe-Home-Desktop.png)
![ABOUT](https://github.com/codebucks27/wibe-studio-starter-files/blob/main/Wibe-About-Desktop.png)
![HOME](https://github.com/codebucks27/wibe-studio-starter-files/blob/main/Wibe-Home-Moblie.png)
![ABOUT](https://github.com/codebucks27/wibe-studio-starter-files/blob/main/Wibe-About-Mobile.png)


### Resources Used in This Project

Fonts: https://fontsource.org/ <br />

### External Libraries used in this project: 

[styled-components](https://styled-components.com/docs/advanced) <br />
[GSAP](https://greensock.com/gsap/) <br />
[Framer-mMtion](https://www.framer.com/motion/) <br />
[React-Locomotive-Scroll](https://www.npmjs.com/package/react-locomotive-scroll) <br />
[Locomotive-Scroll](https://www.npmjs.com/package/locomotive-scroll) <br />

### All The Resources Used in This Website Are from👇:

Walking Girl Video:<br />
Video by cottonbro from Pexels [https://www.pexels.com/@cottonbro]<br />

Images:<br />

Ring: Photo by Arif Syuhada from Pexels<br />
https://www.pexels.com/@arifsyd15<br />

Rings: Photo by cottonbro from Pexels<br />
https://www.pexels.com/@cottonbro<br />

Earings: Photo by say straight from Pexels<br />
https://www.pexels.com/@say-straight-1400349<br />

White Tee:Photo by cottonbro from Pexels<br />
https://www.pexels.com/@cottonbro<br />

black t-shirt girl: Photo by Lena Hsvl from Pexels<br />
https://www.pexels.com/@lenaneva<br />

Red girl: Photo by Yaroslava Borz from Pexels<br />
https://www.pexels.com/@yaroslava-borz-126286496<br />

Ethnic Wear: Photo by Artem Beliaikin from Pexels<br />
https://www.pexels.com/@belart84<br />

Suit: Photo by Chloe from Pexels<br />
https://www.pexels.com/@chloekalaartist<br />

cap male: Photo by cottonbro from Pexels<br />
https://www.pexels.com/@cottonbro<br />

Watches: Photo by Mister Mister from Pexels<br />
https://www.pexels.com/@bemistermister<br />

Denim: Photo by Denis Zagorodniuc from Pexels<br />
https://www.pexels.com/@imdennyz<br />

Jacket: Photo by Simon Robben from Pexels<br />
https://www.pexels.com/@simon-robben-55958<br />

Yellow T-shirt:Photo by RAUL REYNOSO from Pexels<br />
https://www.pexels.com/@raulkingr<br />

Yellow Dress: Photo by Godisable Jacob from Pexels<br />
https://www.pexels.com/@godisable-jacob-226636<br />



### Famous Quotes Used:
"Fashion is the armour to survive the reality of everyday life."<br />
-- bill cunningham

"One is never over-dressed or under-dressed with a Little Black Dress." —Karl Lagerfeld<br />

