# electron-vite-vue

[![awesome-vite](https://awesome.re/mentioned-badge.svg)](https://github.com/vitejs/awesome-vite)
![GitHub license](https://img.shields.io/github/license/caoxiemeihao/electron-vite-vue?style=flat)
![GitHub stars](https://img.shields.io/github/stars/caoxiemeihao/electron-vite-vue?color=fa6470&style=flat)
![GitHub forks](https://img.shields.io/github/forks/caoxiemeihao/electron-vite-vue?style=flat)


**[English](README.md) | ç®ä½ä¸­æ**

ð¥³ Electron + Vite + Vue æ´åæ¨¡æ¿ -- **ç»æç®åï¼å®¹æä¸æï¼**

## å¿«éå¼å§

[![quick-start](https://asciinema.org/a/483731.svg)](https://asciinema.org/a/483731)

## æ¦è¿°

&emsp;&emsp;è¿æ¯ä¸ä¸ªè¿½æ±ç²¾ç®ç`Electron`ç±»æ´åæ¨¡æ¿ï¼åªä¿ææåºæ¬çæä»¶ãæåºæ¬çä¾èµãæåºæ¬çåè½ï¼èä¸æ¯å¤§èå¨çãèè¿çè®¾è®¡ãè¿æ ·åçç®çæ¯è½ç¡®ä¿æ¨¡æ¿è¶³å¤çµæ´»ã

æä»¥è¯´å¦æä½ æ¯å¯¹ -- å·¥ç¨æ¨¡æ¿è¿½æ±ç²¾ç®ç Coderï¼æèåå¥ä¸çå°ç½æ³å¼æç½`Electron`æ´åç±»æ¨¡æ¿æåºç¡çå·¥ä½åçï¼äº¦æèä½ æ¯å¤§ç¥åªæ¯æ³å·æå°å¹²ç¹æ´»ï¼é£ä¹è¿ä¸ªæ¨¡æ¿æåéä½ ä¸è¿äºã

å°½ç®¡å¦æ­¤ï¼æè¿æ¯å¸æä½ å¯¹`Electron` `Vite`æä¸å®çåºç¡ï¼å ä¸ºé¤äºé¡¹ç®ç»æç®åå¤ï¼è¿ä»½`README`ä¹æ¾å¾ âç²¾ç®â ã

æ¨¡æ¿çå·ä½å®ç°ç»èæç¸ä¿¡ä½ çä¸¤éæºç å°±è½æå®åéäº ð

## ç®å½ç»æ

&emsp;&emsp;ä¸æ¦å¯å¨ææåèæ¬æ§è¡è¿ï¼ä¼å¨æ ¹ç®å½äº§ç **`dist` æä»¶å¤¹ï¼éé¢çæä»¶å¤¹å `packages` ä¸æ¨¡ä¸æ ·**ï¼å¨ä½¿ç¨ä¸äºè·¯å¾è®¡ç®æ¶ï¼å°¤å¶æ¯ç¸å¯¹è·¯å¾è®¡ç®ï¼`dist` ä¸ `packages` éé¢ä¿æç¸åçç®å½ç»æè½é¿å¼å¥½å¤é®é¢

```tree
â
âââ dist                      æå»ºåï¼æ ¹æ® packages ç®å½çæ
â   âââ main
â   âââ preload
â   âââ renderer
â
âââ scripts
â   âââ build.mjs             é¡¹ç®å¼åèæ¬ npm run build
â   âââ watch.mjs             é¡¹ç®å¼åèæ¬ npm run dev
â
âââ packages
â   âââ main                  ä¸»è¿ç¨æºç 
â       âââ vite.config.ts
â   âââ preload               é¢å è½½èæ¬æºç 
â       âââ vite.config.ts
â   âââ renderer              æ¸²æè¿ç¨æºç 
â       âââ vite.config.ts
â
```

## ä¸äºå¸¸è§çæ¡ä¾

å¨ Main-process ä¸­ä½¿ç¨ ð [electron-vite-boilerplate](https://github.com/caoxiemeihao/electron-vite-boilerplate)

å¨ Renderer-process ä¸­ä½¿ç¨ ð [electron-vite-boilerplate/tree/nodeIntegration](https://github.com/caoxiemeihao/electron-vite-boilerplate/tree/nodeIntegration)

**ES Modules**

- [execa](https://www.npmjs.com/package/execa)
- [node-fetch](https://www.npmjs.com/package/node-fetch)
- [file-type](https://www.npmjs.com/package/file-type)

**Native Addons**

- [sqlite3](https://www.npmjs.com/package/sqlite3)
- [serialport](https://www.npmjs.com/package/serialport)

## è¿è¡ææ
<img width="400px" src="https://github.com/caoxiemeihao/blog/blob/main/electron-vue-vite/screenshot/electron-15.png?raw=true" />

## <!--å¾®ä¿¡ | | -->è¯·æåæ¯ä¸åè¶ ð¥³

<div style="display:flex;">
  <!-- <img height="333px" src="https://raw.githubusercontent.com/caoxiemeihao/blog/main/assets/wechat/group/qrcode.jpg" />
  &nbsp;&nbsp;&nbsp;&nbsp; -->
  <img height="333px" src="https://raw.githubusercontent.com/caoxiemeihao/blog/main/assets/wechat/%24qrcode/%24.png" />
</div>
