# 🔒 Stealth Mode for Twitter — Hide Your Profile Avatar!  

**Keep your privacy intact while browsing Twitter in public or during live streams!** This custom CSS lets you hide your own profile avatar, minimizing the risk of doxxing and helping you maintain better OPSEC (Operational Security).  

---

## 🚀 Features  
- **Hide your own Twitter avatar:** Prevent accidental identity reveals during streams or in public.  
- **Focus on content:** Declutter your UI and keep the spotlight on tweets, not on you.  
- **Enhanced OPSEC:** Reduce the chances of doxxing by removing recognizable elements.  

---

## 📦 Installation  
1. Install a browser extension like **Stylus** for [chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) & [firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or **Tampermonkey**.
2. Create a new style/script and paste the following CSS:  

   ```css
   /* hide your avatar */
       [data-testid="SideNav_AccountSwitcher_Button"],
   /* change the "x" in UserAvatar-Container-x to the first letter in your twitter username */
       [data-testid*="UserAvatar-Container-x"],
   /* this selector will prevent accidently clicks on "post your reply" */
       [class="DraftEditor-root"]
       {display:none;}

   /* hide messages */
       [class="css-175oi2r r-173mn98 r-1rtiivn r-hvns9x r-1jte41z r-5wli1b"]
       {display:none;}
   ```

3. Save and refresh Twitter. Your avatar should now be hidden!  

---

## 🎥 Perfect for Streamers  
Streaming your screen? This simple CSS trick helps prevent slip-ups by keeping your Twitter identity under wraps. Stream with confidence knowing your OPSEC is covered!  

---

## 📌 Notes  
- This CSS only hides *your own* avatar on your end.  
- No data is collected or transmitted—it's 100% client-side.  

---

## 🤝 Contributions  
Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!  

---

## 📜 License  
GPL 3.0  

---
