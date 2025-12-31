---
layout: splash
title: お問い合わせ
classes: wide
header:
  overlay_image: /assets/images/cn-hero.jpg
  overlay_filter: 0.3
  overlay_color: "#000"
  actions:
    - label: "🇨🇳 中文"
      url: "/cn/contact/"
      class: "btn--outline"  
---

<!-- お問い合わせ案内（先に安心感） -->
<section style="max-width:860px; margin:0 auto; text-align:center;">

  <p style="color:#555; line-height:1.8; margin-bottom:2.2em;">
    当社では、日本国内および中国語圏のお客様を対象に、<br>
    IT・Web・ビジネス支援に関する各種ご相談を承っております。<br>
    <strong>日本語・中国語での対応が可能</strong>です。
  </p>

  <p style="color:#666; font-size:0.95em;">
    オンラインでのご相談も可能です。<br>
    来社をご希望の場合は、下記より事前予約をお願いいたします。
  </p>

</section>

<hr style="margin:4em 0;">

<!-- 来社预约模块 -->
<section style="max-width:980px; margin:0 auto;">

  <h2 style="text-align:center;">来社予約（事前予約制）</h2>
  <p style="text-align:center; color:#666; margin-bottom:2.2em;">
    福岡オフィスへのご来社をご希望の方は、<br>
    下記フォームより事前にお申し込みください。
  </p>

  <div style="
    max-width:720px;
    margin:0 auto;
    background:#fff;
    padding:2.5em 2.5em 2.8em;
    border-radius:18px;
    box-shadow:0 14px 35px rgba(0,0,0,.08);
  ">

    <form action="https://formspree.io/f/mvzowdgl" method="POST">

      <input type="hidden" name="language" value="JP">

      <label>ご来社希望日</label>
      <input type="date" name="visit_date" required>

      <label>ご来社希望時間</label>
      <input type="time" name="visit_time" required>

      <label>ご相談内容・目的</label>
      <textarea name="purpose" rows="3" placeholder="例：Webサイト制作についてのご相談" required></textarea>

      <label>会社名・お名前</label>
      <input type="text" name="name" required>

      <label>メールアドレス</label>
      <input type="email" name="email" required>

      <div style="text-align:center; margin-top:2em;">
        <button type="submit" class="btn btn--primary btn--large">
          内容を送信する
        </button>
      </div>

    </form>

    <p style="text-align:center; font-size:0.85em; color:#888; margin-top:1.8em;">
      ※ 内容を確認後、当社より受付可否のご連絡を差し上げます。<br>
      当社からの確認連絡をもって予約確定となります。
    </p>

  </div>

</section>

<hr style="margin:5em 0;">

<!-- 会社情報・地図 -->
<section style="max-width:1100px; margin:0 auto;">

  <h2 style="text-align:center; margin-bottom:2.5em;">会社情報</h2>

  <div style="
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(320px,1fr));
    gap:2.5em;
    align-items:start;
  ">

    <div style="
      background:#fff;
      padding:2.2em;
      border-radius:18px;
      box-shadow:0 12px 30px rgba(0,0,0,.08);
    ">

      <h3>会社名</h3>
      <p>嘉美技術株式会社<br>JIAMEI Technology Co., Ltd.</p>

      <h3>所在地</h3>
      <p>
        福岡県福岡市中央区平尾一丁目<br>
        <span style="color:#888; font-size:0.9em;">
          ※ 詳細住所は正式なお打ち合わせ後にご案内いたします
        </span>
      </p>

      <h3>担当</h3>
      <p>劉（リュウ）</p>

      <h3>電話番号</h3>
      <p>
        日本：070-8441-3996<br>
        中国：138-0739-1160
      </p>

      <h3>メール</h3>
      <p>68600669@qq.com</p>

    </div>

    <div style="
      background:#fff;
      padding:2.2em;
      border-radius:18px;
      box-shadow:0 12px 30px rgba(0,0,0,.08);
    ">

      <h3 style="margin-bottom:1em;">アクセスマップ</h3>

      <iframe
        src="https://www.google.com/maps?q=福岡県福岡市中央区&output=embed"
        width="100%"
        height="320"
        style="border:0; border-radius:14px;"
        loading="lazy">
      </iframe>

    </div>

  </div>

</section>
