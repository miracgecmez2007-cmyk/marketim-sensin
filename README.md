# marketim-sensin
market uygulaması
Request

{
  "action": "publish",
  "url": "https://claude.ai/artifact/EHWB3hi7z2DWme1LMX3Ty8",
  "file_path": "/mnt/user-data/outputs/marketim-sensin.html",
  "capabilities": {
    "db": {},
    "user": {
      "scopes": [
        "profile"
      ]
    },
    "sample": {}
  }
}
Response

Published /mnt/user-data/outputs/marketim-sensin.html at https://claude.ai/artifact/EHWB3hi7z2DWme1LMX3Ty8

For the next change to this page, call action "edit" with url and edits (old_str/new_str pairs, each old_str copied exactly from the file as it now stands) instead of patching the file with a bash or python script or str_replace and publishing again; that one call changes the file and the page together. View the file first only if its text is no longer in this conversation. To rewrite most of the page, edit the file itself and publish it with url
<!doctype html>
<html lang="tr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Marketim Sensin - M1 Abrams Korumalı & Kâr Payı Destekli</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@700;800&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#F4F7F2;--surf:#fff;--ink:#1B2A22;--mute:#5E6E64;--line:#D9E2DB;--green:#2E7D4F;--tag:#FFD84A;--tagink:#2A2200;--red:#C62222;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#111A14;--surf:#1B261F;--ink:#E8F0EA;--mute:#9DB0A3;--line:#2C3B31;--green:#5BBF85;--red:#B81F1F;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#111A14;--surf:#1B261F;--ink:#E8F0EA;--mute:#9DB0A3;--line:#2C3B31;--green:#5BBF85;--red:#B81F1F;color-scheme:dark}
*,*::before,*::after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.5 "DM Sans",system-ui,sans-serif}
main{max-width:760px;margin:0 auto;padding:20px 16px 48px}
h1,h2,.num{font-family:"Bricolage Grotesque","DM Sans",system-ui,sans-serif}
h1{font-size:2rem;line-height:1.1;margin:8px 0 4px;font-weight:800}
.sub{color:var(--mute);margin:0 0 18px}
h2{font-size:1.2rem;margin:22px 0 10px}
nav{display:flex;gap:6px;border-bottom:2px solid var(--line);margin-bottom:16px}
nav button{flex:1;background:none;border:0;border-bottom:3px solid transparent;margin-bottom:-2px;padding:10px 4px;font:inherit;font-weight:700;color:var(--mute);cursor:pointer}
nav button[aria-selected="true"]{color:var(--ink);border-color:var(--green)}
button:focus-visible,input:focus-visible,select:focus-visible{outline:3px solid var(--green);outline-offset:2px}
input,select{width:100%;font:inherit;color:var(--ink);background:var(--surf);border:1.5px solid var(--line);border-radius:10px;padding:11px 12px}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin:12px 0}
.chip{font:inherit;font-size:.9rem;border:1.5px solid var(--line);background:var(--surf);color:var(--ink);border-radius:99px;padding:6px 13px;cursor:pointer}
.chip[aria-pressed="true"]{background:var(--green);border-color:var(--green);color:#fff}
.card{display:flex;gap:12px;align-items:center;justify-content:space-between;background:var(--surf);border:1.5px solid var(--line);border-radius:12px;padding:12px 14px;margin-bottom:10px}
.card.off{opacity:.55}
.info{min-width:0;flex:1}
.pname{font-weight:700}
.pmk{color:var(--mute);font-size:.85rem}
.unit-price{font-size:.8rem;color:var(--green);font-weight:700;margin-top:2px}
.time-badge{font-size:.75rem;color:var(--mute);font-style:italic}
.tag{background:var(--tag);color:var(--tagink);border-radius:4px 10px 10px 4px;padding:6px 12px;text-align:right;flex:none;min-width:110px;border-left:5px solid var(--green)}
.tag.up{background:#fdf2f2;color:var(--red);border-left-color:var(--red)}
.tag .num{font-size:1.45rem;font-weight:800;line-height:1.1;display:block}
.tag.up .num{color:var(--red)}
.tag s{font-size:.85rem;opacity:.75}
.tag b{font-size:.8rem;margin-left:4px}
.btn{font:inherit;font-weight:700;border:0;border-radius:10px;padding:10px 14px;background:var(--green);color:#fff;cursor:pointer}
.btn.alt{background:none;border:1.5px solid var(--line);color:var(--ink);padding:7px 11px;font-weight:500;font-size:.9rem}
.btn.sm{padding:4px 8px;font-size:.8rem}
.btn:disabled{opacity:.5;cursor:default}
.row{display:flex;gap:8px;margin-top:8px;flex-wrap:wrap;align-items:center}
.col{flex:1;min-width:120px}
label{font-size:.9rem;font-weight:700;display:block;margin-top:12px}
.empty{color:var(--mute);padding:18px;border:1.5px dashed var(--line);border-radius:12px;text-align:center}
.best{border-color:var(--green);border-width:2.5px}
.ok{color:var(--green);font-weight:700}
.miss{color:var(--red)}
.err{color:var(--red);font-weight:700;min-height:1.4em;margin:8px 0 0}
.abrams-alert{background:#fdf2f2;border:1.5px solid var(--red);color:var(--red);padding:10px 12px;border-radius:10px;font-size:0.85rem;font-weight:700;margin-top:8px}
.right{text-align:right;flex:none}
.right .num{font-size:1.2rem;font-weight:800}
.badge{display:inline-block;background:var(--tag);color:var(--tagink);border-radius:99px;padding:0 8px;font-size:.8rem;font-weight:700;margin-left:4px}
.st{color:#C98A00;font-weight:700}
.edit-box{display:flex;gap:4px;align-items:center;margin-top:6px}
.edit-box input{width:80px;padding:4px 6px;font-size:.85rem}
</style>
</head>
<body>
<main>
<h1>Marketim Sensin</h1>
<p class="sub">Mahalledeki marketlerin bugünü tek ekranda (M1 Abrams Korumalı & Kâr Payı Destekli).</p>
<p class="pmk" id="cloud" style="margin:-10px 0 14px"></p>

<nav role="tablist">
<button role="tab" data-tab="today" aria-selected="true">Bugün</button>
<button role="tab" data-tab="list" aria-selected="false">Listem<span class="badge" id="cnt" hidden>0</span></button>
<button role="tab" data-tab="rev" aria-selected="false">Yorumlar</button>
<button role="tab" data-tab="panel" aria-selected="false">Market Paneli</button>
</nav>

<section id="today">
<input id="q" type="search" placeholder="Ürün ara: süt, yumurta, yağ..." aria-label="Ürün ara">

<h2>Kategoriler</h2>
<div class="chips" id="cat-chips"></div>

<h2>Barkod ile Karşılaştır</h2>
<div class="row">
<input id="bc" class="col" style="flex:2" inputmode="numeric" placeholder="Barkod numarası" aria-label="Barkod numarası">
<button class="btn" id="bgo">Karşılaştır</button>
<button class="btn alt" id="bcam">Fotoğrafla Tara</button>
<input id="bf" type="file" accept="image/*" capture="environment" hidden>
</div>
<p class="pmk" id="bmsg" role="status">Denemek için 8690000000011 yaz[cite: 1].</p>
<div id="bres"></div>

<h2>Bugünün Fiyatları & İndirimler</h2>
<div class="chips" id="chips"></div>
<div id="deals"></div>
</section>

<section id="list" hidden>
<h2 style="margin-top:0">Alışveriş Listem</h2>
<div id="mylist"></div>
<h2>Hangi Markette Ne Var & Sepet Maliyeti</h2>
<div id="cover"></div>
</section>

<section id="rev" hidden>
<h2 style="margin-top:0">Market Puanları</h2>
<div id="scores"></div>
<h2>Yorum Yaz</h2>
<label for="rm">Market</label>
<select id="rm"></select>
<label>Puanın</label>
<div class="chips" id="stars" aria-label="Puan"></div>
<label for="rt">Yorumun (isteğe bağlı)</label>
<input id="rt" maxlength="200" placeholder="Taze ürünler, güler yüzlü personel…">
<p class="err" id="rerr" role="alert"></p>
<button class="btn" id="radd">Yorumu Gönder</button>
<h2>Son Yorumlar</h2>
<div id="revs"></div>
</section>

<section id="panel" hidden>
<h2 style="margin-top:0">Ürün / Fiyat Ekle</h2>
<div class="abrams-alert">🛡️ M1 Abrams Savunma Sistemi Aktif: Kontrollü kâr payı eklenmesine izin verilir, ancak fahiş fiyat artışları (%40 üstü) otomatik olarak engellenir.</div>
<label for="pm">Marketiniz</label>
<select id="pm"></select>
<label for="pn">Ürün Adı</label>
<input id="pn" placeholder="Örn. Süt 1 L">
<div class="row">
  <div class="col">
    <label for="pcat">Kategori</label>
    <select id="pcat">
      <option value="Genel">Genel</option>
      <option value="Süt & Kahvaltılık">Süt & Kahvaltılık</option>
      <option value="Temel Gıda">Temel Gıda</option>
      <option value="Meyve & Sebze">Meyve & Sebze</option>
      <option value="Atıştırmalık">Atıştırmalık</option>
    </select>
  </div>
  <div class="col">
    <label for="punit">Birim Ölçüsü</label>
    <input id="punit" placeholder="Örn. 1 L, 500 g, 1 kg">
  </div>
</div>
<label for="pb">Barkod (isteğe bağlı)</label>
<input id="pb" inputmode="numeric" placeholder="Ambalajın üzerindeki numara">
<div class="row">
<div class="col"><label for="po">Normal / Maliyet Fiyatı (₺)</label><input id="po" type="number" inputmode="decimal" min="0" step="0.01"></div>
<div class="col"><label for="pp">Satış / Bugünkü Fiyat (₺)</label><input id="pp" type="number" inputmode="decimal" min="0" step="0.01"></div>
</div>
<p class="err" id="err" role="alert"></p>
<button class="btn" id="add">Yayınla</button>

<h2>Marketinizin Aktif Ürünleri ve Düzenleme</h2>
<div id="mine"></div>
</section>
</main>

<script>
const markets=["Yeşil Market","Hacı Bey Market","Mahalle Bakkalı"];
const categories=["Tümü","Süt & Kahvaltılık","Temel Gıda","Meyve & Sebze","Atıştırmalık"];

function readStored(key,fallback){
  try{const raw=localStorage.getItem("marketim_sensin_"+key);return raw===null?fallback:JSON.parse(raw)}catch(_){return fallback}
}
function writeStored(key,value){try{localStorage.setItem("marketim_sensin_"+key,JSON.stringify(value))}catch(_){} }

const now=Date.now();
let offers=[
{id:1,m:"Yeşil Market",n:"Süt 1 L",cat:"Süt & Kahvaltılık",unit:"1 L",o:42,p:34,s:1,b:"8690000000011",updatedAt:now},
{id:2,m:"Hacı Bey Market",n:"Süt 1 L",cat:"Süt & Kahvaltılık",unit:"1 L",o:40,p:40,s:1,b:"8690000000011",updatedAt:now-3600000*5},
{id:3,m:"Mahalle Bakkalı",n:"Süt 1 L",cat:"Süt & Kahvaltılık",unit:"1 L",o:44,p:44,s:0,b:"8690000000011",updatedAt:now-3600000*24},
{id:4,m:"Yeşil Market",n:"Yumurta 15’li",cat:"Süt & Kahvaltılık",unit:"15 adet",o:95,p:79,s:1,updatedAt:now},
{id:5,m:"Hacı Bey Market",n:"Yumurta 15’li",cat:"Süt & Kahvaltılık",unit:"15 adet",o:92,p:85,s:1,updatedAt:now},
{id:6,m:"Mahalle Bakkalı",n:"Yumurta 15’li",cat:"Süt & Kahvaltılık",unit:"15 adet",o:98,p:98,s:1,updatedAt:now},
{id:7,m:"Yeşil Market",n:"Makarna 500 g",cat:"Temel Gıda",unit:"500 g",o:22,p:22,s:1,updatedAt:now},
{id:8,m:"Hacı Bey Market",n:"Makarna 500 g",cat:"Temel Gıda",unit:"500 g",o:24,p:17,s:1,updatedAt:now},
{id:9,m:"Hacı Bey Market",n:"Domates 1 kg",cat:"Meyve & Sebze",unit:"1 kg",o:60,p:45,s:1,updatedAt:now},
{id:10,m:"Mahalle Bakkalı",n:"Domates 1 kg",cat:"Meyve & Sebze",unit:"1 kg",o:58,p:52,s:1,updatedAt:now},
{id:11,m:"Yeşil Market",n:"Ayçiçek yağı 1 L",cat:"Temel Gıda",unit:"1 L",o:120,p:99,s:1,updatedAt:now},
{id:12,m:"Mahalle Bakkalı",n:"Ekmek",cat:"Temel Gıda",unit:"1 adet",o:12,p:12,s:1,updatedAt:now}
];

offers=readStored("offers",offers);
let list=readStored("list",[]),q="",mk="",cat="Tümü",onlyDeal=false,nid=100;
nid=Math.max(nid,...offers.map(o=>Number(o.id)||0).filter(Number.isFinite))+1;

const $=s=>document.querySelector(s);
const esc=s=>String(s).replace(/[&<>"]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]));
const key=s=>s.trim().toLocaleLowerCase("tr");
const tl=n=>n.toFixed(2).replace(".",",")+" ₺";

// 🛡️ M1 Abrams Fiyat Savunma Algoritması (Kontrollü Kâr Payı Destekli)
function m1AbramsCheck(o, p) {
  // 1. Fahiş Fiyat / Aşırı Kâr Artışı Kalkanı: Bugünkü fiyat, normal fiyatın %40'ından (1.4 katından) fazla artırılamaz.
  if (p > o * 1.40) {
    return "M1 Abrams Kalkanı: Fahiş fiyat artışı tespit edildi! Kâr marjı normal fiyatın en fazla %40 üzerine çıkabilir.";
  }
  // 2. Anormal / Hatalı Düşüş Kalkanı: Fiyat, normal fiyatın %15'inden daha aşağıya düşürülemez.
  if (p < o * 0.15 && o > 5) {
    return "M1 Abrams Kalkanı: Şüpheli fiyat düşüşü! Normal fiyatın çok altında (%85+ indirim) veri girişi engellendi.";
  }
  return null;
}

function timeAgo(ts){
  if(!ts)return "";
  const diff=Math.floor((Date.now()-ts)/60000);
  if(diff<60)return diff<=1?"şimdi":diff+" dk önce";
  const h=Math.floor(diff/60);
  if(h<24)return h+" saat önce";
  return Math.floor(h/24)+" gün önce";
}

function tagHtml(o){
  if(o.p < o.o){
    const d=Math.round((1 - o.p/o.o)*100);
    return `<div class="tag"><span class="num">${tl(o.p)}</span><s>${tl(o.o)}</s><b>%${d} İndirim</b></div>`;
  } else if(o.p > o.o){
    const u=Math.round((o.p/o.o - 1)*100);
    return `<div class="tag up"><span class="num">${tl(o.p)}</span><s>${tl(o.o)}</s><b>+%${u} Artış</b></div>`;
  } else {
    return `<div class="tag"><span class="num">${tl(o.p)}</span><b>Sabit Fiyat</b></div>`;
  }
}

function renderCategories(){
  $("#cat-chips").innerHTML=categories.map(c=>
    `<button class="chip" data-cat="${esc(c)}" aria-pressed="${cat===c}">${esc(c)}</button>`
  ).join("");
}

function renderChips(){
  $("#chips").innerHTML=
    `<button class="chip" data-mk="" aria-pressed="${mk===""}">Tüm Marketler</button>`+
    markets.map(m=>`<button class="chip" data-mk="${esc(m)}" aria-pressed="${mk===m}">${esc(m)}</button>`).join("")+
    `<button class="chip" data-deal="1" aria-pressed="${onlyDeal}">Sadece İndirimli</button>`;
}

function renderDeals(){
  const f=offers.filter(o=>{
    const matchQ=!q||key(o.n).includes(key(q));
    const matchM=!mk||o.m===mk;
    const matchC=cat==="Tümü"||o.cat===cat;
    const matchD=!onlyDeal||o.p<o.o;
    return matchQ&&matchM&&matchC&&matchD;
  }).sort((a,b)=>(b.s-a.s)||(a.p-b.p));

  $("#deals").innerHTML=f.length?f.map(o=>{
    const inL=list.some(n=>key(n)===key(o.n));
    const tBadge=o.updatedAt?`<span class="time-badge"> · Güncelleme: ${timeAgo(o.updatedAt)}</span>`:"";
    const uBadge=o.unit?`<div class="unit-price">Ölçek: ${esc(o.unit)}</div>`:"";
    return `<div class="card ${o.s?"":"off"}">
      <div class="info">
        <div class="pname">${esc(o.n)}</div>
        <div class="pmk">${esc(o.m)}${rate(o.m)}${o.s?"":" · Tükendi"}${tBadge}</div>
        ${uBadge}
        <div class="row" style="margin-top:6px">
          <button class="btn alt" data-addl="${o.id}" ${inL||!o.s?"disabled":""}>${inL?"Listede":"Listeme Ekle"}</button>
        </div>
      </div>
      ${tagHtml(o)}
    </div>`;
  }).join(""):`<div class="empty">Sonuç bulunamadı. Kategori veya filtreleri değiştirmeyi deneyin.</div>`;
}

function renderList(){
  const c=$("#cnt");c.hidden=!list.length;c.textContent=list.length;
  $("#mylist").innerHTML=list.length?list.map((n,i)=>
    `<div class="card"><div class="pname">${esc(n)}</div><button class="btn alt" data-rm="${i}">Çıkar</button></div>`).join("")
    :`<div class="empty">Listeniz boş. Bugün sekmesinden ürün ekleyebilirsiniz.</div>`;

  if(!list.length){$("#cover").innerHTML=`<div class="empty">Ürün ekleyince hangi markette ne kadar ödeyeceğinizi burada göreceksiniz.</div>`;return}

  const rows=markets.map(m=>{
    const found=[],miss=[];let total=0;
    list.forEach(n=>{
      const o=offers.find(x=>x.m===m&&key(x.n)===key(n)&&x.s);
      if(o){found.push(n);total+=o.p}else{miss.push(n)}
    });
    return{m,found,miss,total};
  }).sort((a,b)=>b.found.length-a.found.length||a.total-b.total);

  const bestTotal=rows[0]?.total||0;

  $("#cover").innerHTML=rows.map((r,i)=>{
    const diff=i>0&&r.found.length===list.length?` (+${tl(r.total-bestTotal)})`:"";
    return `<div class="card ${i===0&&r.found.length?"best":""}">
      <div class="info">
        <div class="pname">${esc(r.m)}${rate(r.m)} ${i===0&&r.found.length===list.length?'<span class="badge">En Ucuz Sepet</span>':''}</div>
        <div class="pmk">${r.found.length}/${list.length} ürün bulundu</div>
        <div>${r.miss.length?`<span class="miss">Eksik: ${r.miss.map(esc).join(", ")}</span>`:`<span class="ok">Tamamı stokta var</span>`}</div>
      </div>
      <div class="right">
        <span class="num">${r.found.length?tl(r.total):"–"}</span>
        <div class="pmk">${r.found.length?`Bulunanlar Toplamı${diff}`:"Bulunamadı"}</div>
      </div>
    </div>`;
  }).join("");
}

function renderPanel(){
  const m=$("#pm").value;
  const mine=offers.filter(o=>o.m===m);
  $("#mine").innerHTML=mine.length?mine.map(o=>
    `<div class="card ${o.s?"":"off"}">
      <div class="info">
        <div class="pname">${esc(o.n)} <span class="pmk">(${esc(o.cat||"Genel")})</span></div>
        <div class="pmk">Barkod: ${o.b||"Yok"} · Güncelleme: ${timeAgo(o.updatedAt)}</div>
        <div class="edit-box">
          <input type="number" step="0.01" id="ep-${o.id}" value="${o.p}" placeholder="Yeni Fiyat">
          <button class="btn sm" data-updatep="${o.id}">Fiyatı Güncelle</button>
        </div>
        <div class="row" style="margin-top:6px">
          <button class="btn alt sm" data-stock="${o.id}">${o.s?"Tükendi Yap":"Stokta Yap"}</button>
          <button class="btn alt sm" data-del="${o.id}">Sil</button>
        </div>
      </div>
      ${tagHtml(o)}
    </div>`).join("")
    :`<div class="empty">Henüz bu markete ait ürün bulunmuyor.</div>`;
}

function renderAll(){
  writeStored("offers",offers);writeStored("list",list);writeStored("reviews",reviews);
  renderCategories();renderChips();renderDeals();renderList();renderPanel();renderRev();
}

$("#pm").innerHTML=markets.map(m=>`<option>${esc(m)}</option>`).join("");
$("#pm").onchange=renderPanel;
$("#q").oninput=e=>{q=e.target.value;renderDeals()};

$("#add").onclick=()=>{
  const n=$("#pn").value.trim(),o=parseFloat($("#po").value),p=parseFloat($("#pp").value),e=$("#err");
  if(!n){e.textContent="Lütfen ürün adını girin.";return}
  if(!(o>0)||!(p>0)){e.textContent="Lütfen geçerli fiyatlar girin.";return}
  
  // M1 Abrams Kalkanı Kontrolü (Kontrollü kâr payı artışlarına izin verir, fahiş olanları engeller)
  const defenseError = m1AbramsCheck(o, p);
  if(defenseError){e.textContent=defenseError;return}

  e.textContent="";
  const b=$("#pb").value.replace(/\D/g,"");
  const catVal=$("#pcat").value;
  const unitVal=$("#punit").value.trim();

  save({m:$("#pm").value,n,cat:catVal,unit:unitVal,o,p,s:1,updatedAt:Date.now(),...(b?{b}:{})});
  $("#pn").value=$("#po").value=$("#pp").value=$("#pb").value=$("#punit").value="";
  renderAll();
};

document.addEventListener("click",e=>{
  const t=e.target.closest("button");if(!t)return;
  const d=t.dataset;
  if(d.tab){
    document.querySelectorAll("nav button").forEach(b=>b.setAttribute("aria-selected",b===t));
    ["today","list","rev","panel"].forEach(id=>$("#"+id).hidden=id!==d.tab);
  }else if(d.cat!==undefined){cat=d.cat;renderCategories();renderDeals()}
  else if(d.mk!==undefined){mk=d.mk;renderChips();renderDeals()}
  else if(d.deal){onlyDeal=!onlyDeal;renderChips();renderDeals()}
  else if(d.addl){const o=offers.find(x=>x.id==d.addl);if(o&&!list.some(n=>key(n)===key(o.n))){list.push(o.n);renderAll()}}
  else if(d.rm!==undefined){list.splice(+d.rm,1);renderAll()}
  else if(d.stock){setStock(offers.find(x=>x.id==d.stock))}
  else if(d.del){remove(d.del)}
  else if(d.updatep){
    const id=d.updatep;
    const val=parseFloat($("#ep-"+id).value);
    if(val>0)updatePrice(id,val);
  }
});

function compare(code){
  code=code.replace(/\D/g,"");
  const msg=$("#bmsg"),box=$("#bres");box.innerHTML="";
  if(code.length<8){msg.textContent="Geçerli bir barkod girin (en az 8 rakam).";return}
  const hit=offers.find(o=>o.b===code);
  if(!hit){msg.textContent="Bu barkod henüz sistemde kayıtlı değil.";return}
  msg.textContent="";
  const rows=offers.filter(o=>o.b===code||key(o.n)===key(hit.n)).sort((a,b)=>(b.s-a.s)||(a.p-b.p));
  const best=rows.find(o=>o.s);
  const inL=list.some(n=>key(n)===key(hit.n));
  box.innerHTML=`<h2 style="margin-top:10px">${esc(hit.n)} Karşılaştırması</h2>`+rows.map(o=>{
    const top=best&&o.id===best.id;
    const note=!o.s?"Tükendi":top?"En ucuz seçenek":"+"+tl(o.p-best.p)+" fark var";
    return `<div class="card ${top?"best":""} ${o.s?"":"off"}">
      <div class="info">
        <div class="pname">${esc(o.m)}${rate(o.m)}</div>
        <div class="pmk">${note} · Son Güncelleme: ${timeAgo(o.updatedAt)}</div>
      </div>
      ${tagHtml(o)}
    </div>`;
  }).join("")+`<button class="btn" data-addn="${esc(hit.n)}" ${inL?"disabled":""}>${inL?"Listede Var":"Listeme Ekle"}</button>`;
}

$("#bgo").onclick=()=>compare($("#bc").value);
$("#bc").onkeydown=e=>{if(e.key==="Enter")compare(e.target.value)};
$("#bcam").onclick=()=>$("#bf").click();
$("#bf").onchange=async e=>{
  const f=e.target.files[0];e.target.value="";if(!f)return;
  const msg=$("#bmsg");
  if(!("BarcodeDetector" in window)){msg.textContent="Tarayıcınız barkod okumayı desteklemiyor.";return}
  msg.textContent="Okunuyor…";
  try{
    const r=await new BarcodeDetector().detect(await createImageBitmap(f));
    if(!r.length){msg.textContent="Barkod okunamadı. Numarayı elle yazabilirsiniz.";return}
    $("#bc").value=r[0].rawValue;compare(r[0].rawValue);
  }catch(err){msg.textContent="Barkod taranamadı."}
};

document.addEventListener("click",e=>{
  const a=e.target.closest("button[data-addn]");
  if(a&&!list.some(x=>key(x)===key(a.dataset.addn))){
    list.push(a.dataset.addn);renderAll();a.disabled=true;a.textContent="Listede Var";
  }
});

let reviews=readStored("reviews",[]),stars=0;
function stat(m){const r=reviews.filter(x=>x.m===m);if(!r.length)return null;const a=r.reduce((s,x)=>s+x.r,0)/r.length;return{a,n:r.length,sat:Math.round(100*r.filter(x=>x.r>=4).length/r.length)}}
function rate(m){const s=stat(m);return s?` <span class="st">★ ${s.a.toFixed(1).replace(".",",")}</span>`:""}
function renderStars(){$("#stars").innerHTML=[1,2,3,4,5].map(i=>`<button class="chip" data-star="${i}" aria-pressed="${stars===i}">${i} ★</button>`).join("")}
function renderRev(){
  $("#scores").innerHTML=markets.map(m=>{const s=stat(m);return `<div class="card"><div class="info"><div class="pname">${esc(m)}</div><div class="pmk">${s?s.n+" yorum":"Henüz yorum yok"}</div></div>`+(s?`<div class="right"><span class="num st">★ ${s.a.toFixed(1).replace(".",",")}</span><div class="pmk">Memnuniyet %${s.sat}</div></div>`:"")+`</div>`}).join("");
  const l=[...reviews].sort((a,b)=>b.at-a.at).slice(0,20);
  $("#revs").innerHTML=l.length?l.map(x=>`<div class="card"><div class="info"><div class="pname">${esc(x.m)} <span class="st">${"★".repeat(x.r)}${"☆".repeat(5-x.r)}</span></div>${x.t?`<div>${esc(x.t)}</div>`:""}<div class="pmk">${x.at?new Date(x.at).toLocaleDateString("tr-TR"):""}</div></div></div>`).join(""):`<div class="empty">Henüz yorum yok. İlk yorumu siz yazın.</div>`;
}

$("#rm").innerHTML=markets.map(m=>`<option>${esc(m)}</option>`).join("");
renderStars();
document.addEventListener("click",e=>{const t=e.target.closest("button[data-star]");if(t){stars=+t.dataset.star;renderStars()}});

$("#radd").onclick=()=>{
  const e=$("#rerr");
  if(!stars){e.textContent="Lütfen bir puan seçin.";return}
  e.textContent="";
  const x={m:$("#rm").value,r:stars,t:$("#rt").value.trim().slice(0,200),at:Date.now()};
  if(db)db.collection("reviews").add(x).catch(()=>{e.textContent="Kaydedilemedi."});
  else{reviews.push({id:"l"+nid++,...x});renderAll()}
  $("#rt").value="";stars=0;renderStars();
};

let db=null;
const fail=()=>{$("#err").textContent="Kaydedilemedi. Yetki sorunu."};
function save(x){if(db)db.collection("offers").add(x).catch(fail);else offers.push({id:nid++,...x})}
function setStock(o){if(!o)return;if(db)db.doc("offers/"+o.id).update({s:o.s?0:1,updatedAt:Date.now()}).catch(fail);else{o.s=o.s?0:1;o.updatedAt=Date.now();renderAll()}}

function updatePrice(id,newPrice){
  const o=offers.find(x=>x.id==id);
  if(!o)return;
  
  // Güncelleme sırasında M1 Abrams Kalkanı kontrolü (Kontrollü kâr artışı)
  const defenseError = m1AbramsCheck(o.o, newPrice);
  if(defenseError){
    alert(defenseError);
    return;
  }

  if(db)db.doc("offers/"+id).update({p:newPrice,updatedAt:Date.now()}).catch(fail);
  else{o.p=newPrice;o.updatedAt=Date.now();renderAll()}
}

function remove(id){if(db)db.doc("offers/"+id).delete().catch(fail);else{offers=offers.filter(x=>x.id!=id);renderAll()}}

renderAll();
$("#cloud").textContent="Bulut bağlantısı kontrol ediliyor…";
(window.claude?claude.use("db"):Promise.resolve(null)).then(d=>{
  if(!d){$("#cloud").textContent="Lokal mod: Değişiklikler yerel depolamada saklanıyor.";return}
  db=d;
  d.collection("offers").onSnapshot(s=>{
    offers=s.docs.map(x=>({id:x.id,...x.data()}));
    $("#cloud").textContent="Bulut bağlı: Veriler canlı senkronize ediliyor.";
    renderAll();
  },()=>{db=null;$("#cloud").textContent="Bulut bağlantısı koptu (Yerel Moda Geçildi)."});
  d.collection("reviews").onSnapshot(s=>{
    reviews=s.docs.map(x=>{const v=x.data();return{id:x.id,m:String(v.m),r:Math.min(5,Math.max(1,Math.round(+v.r)||1)),t:String(v.t||""),at:+v.at||0}});
    renderAll();
  },()=>{});
}).catch(()=>{$("#cloud").textContent="Lokal mod: Değişiklikler yerel depolamada saklanıyor."});
</script>
</body>
</html>
