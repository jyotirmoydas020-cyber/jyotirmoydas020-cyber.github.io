# jyotirmoydas020-cyber.github.io
My WhatsApp contact page
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Parthasarathi Das</title>
<style>
:root{--bg:#05060f;--cyan:#19e6ff;--magenta:#ff2bd6;--green:#25d366;--text:#eaf6ff}
*{box-sizing:border-box;margin:0;padding:0}
html,body{min-height:100%}
body{
  font-family:"Trebuchet MS","Segoe UI",system-ui,sans-serif;
  background:
    radial-gradient(circle at 15% 10%,rgba(25,230,255,.18),transparent 45%),
    radial-gradient(circle at 85% 90%,rgba(255,43,214,.18),transparent 45%),
    var(--bg);
  color:var(--text);
  display:flex;justify-content:center;
  padding:32px 20px;
}
main{width:100%;max-width:420px;text-align:center;display:flex;flex-direction:column;align-items:center;gap:26px}
.photo{
  width:min(78vw,300px);aspect-ratio:1;border-radius:50%;padding:5px;
  background:linear-gradient(135deg,var(--cyan),var(--magenta));
  box-shadow:0 0 22px rgba(25,230,255,.7),0 0 60px rgba(255,43,214,.45);
}
.photo img{width:100%;height:100%;object-fit:cover;object-position:center 20%;border-radius:50%;display:block;background:#fff;border:4px solid var(--bg)}
h1{
  font-size:clamp(1.8rem,8vw,2.4rem);letter-spacing:.04em;font-weight:700;color:#fff;
  text-shadow:0 0 6px var(--cyan),0 0 18px var(--cyan),0 0 36px var(--magenta);
}
.wa{
  width:92px;height:92px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  background:rgba(37,211,102,.1);border:2px solid var(--green);
  box-shadow:0 0 14px var(--green),0 0 40px rgba(37,211,102,.55),inset 0 0 14px rgba(37,211,102,.4);
  transition:transform .2s;
}
.wa:hover{transform:scale(1.08)}
.wa svg{width:50px;height:50px;fill:var(--green);filter:drop-shadow(0 0 6px var(--green))}
.hint{font-size:1.05rem;line-height:1.5;color:#cfe9f5;max-width:30ch}
.hint b{color:#fff}
</style>
</head>
<body>
<main>
  <div class="photo"><img src="photo.jpg" alt="Parthasarathi Das"></div>
  <h1>Parthasarathi Das</h1>
  <a class="wa" href="https://wa.me/919233368884" aria-label="Chat on WhatsApp">
    <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
  </a>
  <p class="hint">Click on the logo to chat with <b>Parthasarathi Das</b> on WhatsApp</p>
</main>
</body>
</html>
