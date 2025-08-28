# Vulners Rules Mirror

This repository provides a **mirror of the `rules.json` file** from [Vulners](https://vulners.com/) for use with the [Burp Suite Vulners Software Vulnerability Scanner plugin](https://portswigger.net/bappstore/c9fb79369b56407792a7104e3c4352fb)

⚠️ This repo exists for situations where direct access to the Vulners API/domain is **blocked or filtered** during client engagements or in restricted environments.  

---

## Usage

1. Open **Burp Suite**  
2. Navigate to:  
   `Vulners Software Vulnerability Scanner` → `Scan Rules`  
3. In the **Scan Rules** field, enter: ` https://raw.githubusercontent.com/Darkcast/vulners_rules/refs/heads/main/rules.json `

4. Press the load button  

---

## Why?

In some environments, access to `vulners.com` may be restricted. By hosting a static copy of the official `rules.json`, you can still run the plugin without relying on live access to Vulners infrastructure.  

---

## Notes

- This repo does **not** modify the rules file — it’s a direct copy from Vulners.  
- Update frequency: manual sync with the official Vulners repo.    

---

## Credits

- [Vulners](https://vulners.com/) for maintaining the original vulnerability intelligence and rules.  
- This repo is just a **convenience mirror** for red teamers, pentesters, and researchers working in restricted environments.  
