# Diwali page design QA

- Reference used earlier: `C:\Users\DELL\Downloads\happy_diwali_outdo_system.zip` for the two-screen flow and original layout.
- Current page: `diwali-greeting.html`.
- Branding: uses the supplied white Outdo System logo variant, centered and flanked by animated diya images in both screen headers.
- Rocket service labels: every service rocket cycles through the full service list and updates one dedicated badge in the upper part of the screen. The badge sits outside the greeting content, so it stays visible during the rocket-written greeting and never covers the greeting text. Phone labels are 12px.
- Phone layout: both screens fit the dynamic viewport, with compact short-height styles and scrolling locked.
- Phone background: uses the supplied Diwali image on both screens with a dark readability overlay; desktop background remains unchanged.
- Background diya: the supplied phone background is shown without any added flame or glow overlay.
- Entry-screen diya: uses the supplied transparent PNG at `diwali-assets/diya.png`; its alpha channel is preserved, with an animated flame overlay and pulsing glow so the static image looks lit.
- Requested revision: removed the side Anaar video and the Phuljhadi and Chakri displays. The canvas-based rocket fireworks remain.
- Personalized launch: after name submission, the first gold rocket bursts; its light sweeps across large cursive neon lettering for “Happy” and “Diwali!”, followed by the visitor's name and “From Outdo System.” Small colored bursts frame the lettering; the main greeting appears after the writing fades.
- Browser visual QA remains unavailable: the app refused the local `file://` URL under its URL policy, so the revised rendering was not captured or visually checked.
- Result: code updated; visual QA blocked.
