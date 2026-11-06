---
title: "Bio"
---

# Donglai Luo

Asia Pacific Exchange (APEX)  
Ph.D. in Economics, University of Technology Sydney (UTS)  

Email: <span id="contact-email"><noscript><span style="unicode-bidi:bidi-override;direction:rtl;">ua.ude.stu.tneduts<span>&#64;</span>oul.ialgnod</span></noscript></span>  
GitHub: [github.com/winteraspect](https://github.com/winteraspect)  
Location: Singapore / Sydney, Australia  

---

## Biography

<img src="/IMG_1729.jpeg" style="max-width: 150px; float: right; margin: 0 0 15px 20px; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.08);" alt="Donglai Luo" />

I am a financial economist and quant researcher working at the intersection of Financial Economics, Market Design, and International Finance. 

Currently, I work at the Asia Pacific Exchange (APEX) in Singapore, focusing on quantitative risk management for exchange-traded financial derivatives. I hold a Ph.D. in Economics from the University of Technology Sydney (UTS) Business School.

Prior to joining APEX, I worked as a Research Associate at the Lee Kuan Yew School of Public Policy, National University of Singapore (NUS) from 2017 to 2022, researching international capital flows, financial contagions, and macroprudential policies. I have also spent time as a Senior Economist at the Royal Institution of Chartered Surveyors (RICS).

---

## Research Interests

*   Financial Economics
*   Market Design
*   International Finance

---

## Software & Code

*   [**derivative**](https://github.com/winteraspect/derivative): Pricing and risk engine for OTC exotic commodity and crypto derivatives in Julia, with cross-language benchmarks (Julia, C++, Rust, Python).
*   [**Climate**](https://github.com/winteraspect/Climate): Empirical analysis of climate anomalies (ENSO) and agricultural commodity market tail risks via quantile regression in R.

More code and research repositories are available on [GitHub](https://github.com/winteraspect).

<script>
(function() {
  var target = document.getElementById("contact-email");
  if (!target) return;
  var enc = [105, 116, 115, 108, 113, 102, 110, 51, 113, 122, 116, 69, 120, 121, 122, 105, 106, 115, 121, 51, 122, 121, 120, 51, 106, 105, 122, 51, 102, 122];
  var email = enc.map(function(c) { return String.fromCharCode(c - 5); }).join("");
  var parts = email.split("@");

  var a = document.createElement("a");
  a.innerHTML = parts[0] + "&#8203;@&#8203;" + parts[1];
  a.href = "javascript:void(0)";
  a.title = "Click to send email";
  a.style.cursor = "pointer";

  var activated = false;
  function activate() {
    if (!activated) {
      a.href = "mai" + "lto:" + email;
      activated = true;
    }
  }

  a.addEventListener("pointerover", activate, { once: true });
  a.addEventListener("mouseover", activate, { once: true });
  a.addEventListener("focus", activate, { once: true });
  a.addEventListener("touchstart", activate, { passive: true, once: true });
  a.addEventListener("click", function(e) {
    activate();
    window.location.href = "mai" + "lto:" + email;
  });

  a.addEventListener("copy", function(e) {
    if (e.clipboardData) {
      e.clipboardData.setData("text/plain", email);
      e.preventDefault();
    }
  });

  target.innerHTML = "";
  target.appendChild(a);
})();
</script>


