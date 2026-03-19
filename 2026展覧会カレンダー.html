<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>2026 展覧会カレンダー</title>

<style>
body {
    font-family: sans-serif;
    margin: 20px;
    background: #fafafa;
}

/* ===== 月スケール ===== */
.months {
    display: grid;
    grid-template-columns: repeat(13, 1fr);
    font-size: 12px;
    color: #666;
    margin-bottom: 5px;
}

.month {
    text-align: center;
    border-right: 1px solid #eee;
}

/* グリッドライン */
.grid {
    position: relative;
    height: 420px;
    border-top: 2px solid #ccc;
    background: repeating-linear-gradient(
        to right,
        transparent,
        transparent calc(100%/13 - 1px),
        #eee calc(100%/13)
    );
}

/* 今日ライン */
.today-line {
    position: absolute;
    top: 0;
    bottom: 0;
    width: 2px;
    background: red;
    z-index: 5;
}

/* イベント */
.event {
    position: absolute;
    height: 90px;
    border-radius: 8px;
    padding: 8px;
    color: #fff;
    font-size: 12px;
    overflow: hidden;
    transition: transform 0.2s;
}

.event:hover {
    transform: scale(1.05);
}

/* 色分類 */
.japanese { background: #d35400; }
.western  { background: #2980b9; }
.mixed    { background: #7f8c8d; }

/* 開催中 */
.active {
    outline: 3px solid #fff;
    box-shadow: 0 0 12px rgba(255,255,255,0.9);
}

/* 段 */
.row1 { top: 10px; }
.row2 { top: 110px; }
.row3 { top: 210px; }
.row4 { top: 310px; }

/* サムネ */
.tooltip {
    display: none;
    position: absolute;
    top: -90px;
    left: 0;
    width: 140px;
    height: 90px;
    background-size: cover;
    border-radius: 6px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.event:hover .tooltip {
    display: block;
}

/* スマホ */
@media (max-width: 600px) {
    .grid { height: 700px; }
    .event { font-size: 10px; }
}
</style>
</head>

<body>

<h2>2026 展覧会カレンダー</h2>

<!-- 月スケール -->
<div class="months">
    <div class="month">2月</div>
    <div class="month">3月</div>
    <div class="month">4月</div>
    <div class="month">5月</div>
    <div class="month">6月</div>
    <div class="month">7月</div>
    <div class="month">8月</div>
    <div class="month">9月</div>
    <div class="month">10月</div>
    <div class="month">11月</div>
    <div class="month">12月</div>
    <div class="month">1月</div>
    <div class="month">2月</div>
</div>

<div class="grid" id="timeline">
    <div class="today-line" id="todayLine"></div>
</div>

<script>

/* データ */
const events = [
{ title:"YBA", start:"2026-02-11", end:"2026-05-11", type:"western", url:"https://www.ybabeyond.jp", img:"https://via.placeholder.com/140x90" },
{ title:"下村観山", start:"2026-03-17", end:"2026-05-10", type:"japanese", url:"https://art.nikkei.com/kanzan/", img:"https://via.placeholder.com/140x90" },
{ title:"牧野邦夫", start:"2026-03-31", end:"2026-06-07", type:"western", url:"https://www.chigasaki-museum.jp/exhibition/9811/", img:"https://via.placeholder.com/140x90" },
{ title:"北野天神", start:"2026-04-18", end:"2026-06-14", type:"japanese", url:"https://kitano-tenjin2026.com", img:"https://via.placeholder.com/140x90" },
{ title:"小磯良平", start:"2026-04-18", end:"2026-06-21", type:"western", url:"https://www.fukuoka-art-museum.jp/exhibition/koisoryohei_illusory_masterpiece/", img:"https://via.placeholder.com/140x90" },
{ title:"今村紫紅", start:"2026-04-25", end:"2026-06-28", type:"japanese", url:"https://yokohama.art.museum/exhibition/202604_imamurashiko/", img:"https://via.placeholder.com/140x90" },
{ title:"ルーヴル", start:"2026-09-09", end:"2026-12-13", type:"western", url:"https://www.ntv.co.jp/louvre2026/", img:"https://via.placeholder.com/140x90" },
{ title:"竹久夢二", start:"2026-10-23", end:"2027-01-11", type:"japanese", url:"https://www.momat.go.jp/exhibitions/570", img:"https://via.placeholder.com/140x90" },
{ title:"ターナー", start:"2026-10-24", end:"2027-02-21", type:"western", url:"https://www.nmwa.go.jp/jp/exhibitions/2026turner.html", img:"https://via.placeholder.com/140x90" }
];

const startBase = new Date("2026-02-01");
const endBase   = new Date("2027-02-28");
const total = endBase - startBase;

const timeline = document.getElementById("timeline");

/* イベント描画 */
events.forEach((e, i) => {
    const el = document.createElement("div");
    el.className = `event ${e.type} row${(i%4)+1}`;

    const s = new Date(e.start);
    const ed = new Date(e.end);

    const left = (s - startBase) / total * 100;
    const width = (ed - s) / total * 100;

    el.style.left = left + "%";
    el.style.width = width + "%";

    const today = new Date();

    /* 開催中ハイライト */
    if (today >= s && today <= ed) {
        el.classList.add("active");
    }

    el.innerHTML = `
        <div class="tooltip" style="background-image:url('${e.img}')"></div>
        <b>${e.title}</b><br>
        ${e.start.slice(5)} - ${e.end.slice(5)}<br>
        <a href="${e.url}" target="_blank">公式</a>
    `;

    timeline.appendChild(el);
});

/* 今日ライン */
const today = new Date();
const pos = (today - startBase) / total * 100;
document.getElementById("todayLine").style.left = pos + "%";

</script>

</body>
</html>