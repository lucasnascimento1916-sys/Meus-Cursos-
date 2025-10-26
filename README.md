<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lucas do Nascimento Soares — Cursos e Aulas</title>
  <meta name="description" content="Cursos online de Cálculo, Física e Eletromagnetismo com aulas passo a passo, material em PDF e suporte pelo WhatsApp." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1020;          /* fundo principal escuro elegante */
      --ink:#f4f6fb;         /* texto principal */
      --muted:#aab3c7;       /* texto secundário */
      --brand:#34d399;       /* verde água (cta) */
      --brand-2:#60a5fa;     /* azul suave */
      --card:#121831;        /* cartões */
      --stroke:#1f2a4a;      /* bordas sutis */
      --warning:#f59e0b;
      --danger:#ef4444;
      --radius:18px;
      --shadow:0 10px 35px rgba(0,0,0,.25);
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0;background:linear-gradient(120deg,#0a0f1f 0%,#0d1430 80%);color:var(--ink);font:16px/1.6 "Inter",system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .wrap{width:min(1150px,92vw);margin-inline:auto}
    header{position:sticky;top:0;z-index:50;background:rgba(8,12,28,.55);backdrop-filter:saturate(140%) blur(12px);border-bottom:1px solid var(--stroke)}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:14px 8px}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:38px;height:38px;border-radius:12px;background:linear-gradient(135deg,var(--brand) 0%,var(--brand-2) 100%);box-shadow:inset 0 0 18px rgba(255,255,255,.25)}
    .brand h1{font-size:17px;margin:0;font-weight:700;letter-spacing:.2px}
    .menu{display:flex;gap:18px;align-items:center}
    .menu a{padding:10px 12px;border-radius:10px;color:var(--muted)}
    .menu a:hover{background:rgba(255,255,255,.06);color:var(--ink)}
    .cta{background:linear-gradient(90deg,var(--brand),var(--brand-2));color:#0b1225;padding:10px 16px;font-weight:700;border-radius:12px;box-shadow:var(--shadow);border:0;cursor:pointer}
    .cta:hover{filter:brightness(1.05)}/* hero */
.hero{padding:76px 0 46px;border-bottom:1px solid var(--stroke)}
.hero-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:36px;align-items:center}
.badge{display:inline-flex;align-items:center;gap:8px;color:#0f172a;background:linear-gradient(90deg,#a7f3d0 0%, #bfdbfe 100%);border-radius:999px;padding:8px 12px;font-weight:700}
.badge small{opacity:.85}
.hero h2{font-size:44px;line-height:1.12;margin:14px 0 12px}
.hero p{color:var(--muted);font-size:18px}
.hero-actions{display:flex;gap:14px;align-items:center;margin-top:18px}
.ghost{background:transparent;border:1px solid var(--stroke);padding:10px 16px;border-radius:12px;color:var(--ink)}
.card{background:var(--card);border:1px solid var(--stroke);border-radius:var(--radius);box-shadow:var(--shadow)}
.preview{padding:14px}
.video{position:relative;border-radius:14px;overflow:hidden;border:1px solid var(--stroke)}
.video::after{content:"";position:absolute;inset:0;box-shadow:inset 0 -140px 120px -60px rgba(11,16,32,.85)}

/* cursos */
section{padding:56px 0}
h3{font-size:28px;margin:0 0 8px}
.lead{color:var(--muted);margin:0 0 22px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.course{display:flex;flex-direction:column}
.course .thumb{height:160px;background:linear-gradient(135deg,#0f172a,#111827);border-bottom:1px solid var(--stroke)}
.course .body{padding:16px}
.course h4{margin:0 0 8px}
.tags{display:flex;flex-wrap:wrap;gap:8px;margin:6px 0 14px}
.tag{font-size:12px;padding:6px 10px;border-radius:999px;border:1px solid var(--stroke);color:var(--muted)}
.price{display:flex;align-items:baseline;gap:8px;margin:8px 0 14px}
.price strong{font-size:22px}
.muted{color:var(--muted)}
.buy{margin-top:auto;display:flex;gap:10px}
.btn{display:inline-flex;align-items:center;justify-content:center;padding:10px 14px;border-radius:12px;border:1px solid var(--stroke);cursor:pointer}
.btn.primary{border:0;background:linear-gradient(90deg,var(--brand),var(--brand-2));color:#0b1225;font-weight:800}

/* depoimentos */
.quotes{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.quote{padding:18px}
.quote p{margin:0 0 12px}
.quote .who{display:flex;align-items:center;gap:10px;color:var(--muted)}
.avatar{width:36px;height:36px;border-radius:50%;background:linear-gradient(135deg,#64748b,#1f2937)}

/* FAQ */
details{background:var(--card);border:1px solid var(--stroke);padding:16px;border-radius:14px}
details+details{margin-top:10px}
summary{cursor:pointer;font-weight:600}
summary::marker{color:var(--brand)}
.faq small{color:var(--muted)}

/* rodapé & contato */
footer{padding:36px 0;border-top:1px solid var(--stroke);color:var(--muted)}
.contact{display:grid;grid-template-columns:1fr 1fr;gap:18px}
input,textarea{width:100%;background:#0d1430;color:var(--ink);border:1px solid var(--stroke);border-radius:12px;padding:12px 14px;font:inherit}
textarea{min-height:120px}

/* responsivo */
@media (max-width:980px){
  .hero-grid{grid-template-columns:1fr}
  .grid{grid-template-columns:1fr 1fr}
  .quotes{grid-template-columns:1fr 1fr}
  .contact{grid-template-columns:1fr}
}
@media (max-width:640px){
  .menu{display:none}
  .hero h2{font-size:34px}
  .grid,.quotes{grid-template-columns:1fr}
}

  </style>
</head>
<body>
  <header>
    <div class="wrap nav">
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <h1>Lucas do Nascimento Soares</h1>
      </div>
      <nav class="menu">
        <a href="#cursos">Cursos</a>
        <a href="#depoimentos">Depoimentos</a>
        <a href="#faq">FAQ</a>
        <a href="#contato">Contato</a>
        <a class="cta" href="#cursos">Começar agora</a>
      </nav>
    </div>
  </header>  <main>
    <section class="hero">
      <div class="wrap hero-grid">
        <div>
          <span class="badge">🚀 <small>Aprenda do zero ao avançado</small></span>
          <h2>Cursos de Cálculo, Física e Eletromagnetismo — com passo a passo, exercícios e suporte.</h2>
          <p>
            Estude com materiais didáticos, listas em PDF, videoaulas objetivas e acompanhamento por WhatsApp.
            Acesso por 12 meses, certificado e garantia de 7 dias.
          </p>
          <div class="hero-actions">
            <a class="cta" href="#cursos">Ver cursos</a>
            <a class="ghost" href="#contato">Falar no WhatsApp</a>
          </div>
        </div>
        <div class="card preview">
          <div class="video">
            <!-- Substitua "123456789" pelo ID do seu vídeo do Vimeo (ou YouTube embed). -->
            <iframe title="Aula de amostra" src="https://player.vimeo.com/video/76979871?h=8272103f6e" width="100%" height="320" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
          </div>
          <p class="muted" style="margin:10px 6px 6px">👆 Vídeo de amostra (substituir pelo seu). Proteja conteúdos pagos com Vimeo/Privado.</p>
        </div>
      </div>
    </section><section id="cursos">
  <div class="wrap">
    <h3>📚 Cursos</h3>
    <p class="lead">Escolha seu curso e comece agora. Pagamento em cartão/boleto e acesso imediato.</p>

    <div class="grid">
      <!-- Curso 1 -->
      <article class="course card">
        <div class="thumb" style="background:linear-gradient(135deg,#22d3ee,#34d399)"></div>
        <div class="body">
          <h4>Cálculo I — Limites, Derivadas e Aplicações</h4>
          <div class="tags">
            <span class="tag">+40 aulas</span>
            <span class="tag">PDFs</span>
            <span class="tag">Listas resolvidas</span>
          </div>
          <p class="muted">Domine limites, regras de derivação e problemas clássicos de otimização com passo a passo.</p>
          <div class="price"><strong>R$ 97</strong> <span class="muted">à vista</span></div>
          <div class="buy">
            <a class="btn" href="#" data-checkout="calc1">Ver currículo</a>
            <a class="btn primary" href="#" data-pay="calc1">Comprar agora</a>
          </div>
        </div>
      </article>

      <!-- Curso 2 -->
      <article class="course card">
        <div class="thumb" style="background:linear-gradient(135deg,#60a5fa,#818cf8)"></div>
        <div class="body">
          <h4>Física Mecânica — Cinemática a Dinâmica</h4>
          <div class="tags">
            <span class="tag">+35 aulas</span>
            <span class="tag">Exercícios ENEM/IME/ITA</span>
            <span class="tag">Simulados</span>
          </div>
          <p class="muted">Do básico ao avançado em vetores, MRU, MRUV, forças, trabalho e energia.</p>
          <div class="price"><strong>R$ 97</strong> <span class="muted">à vista</span></div>
          <div class="buy">
            <a class="btn" href="#" data-checkout="fis1">Ver currículo</a>
            <a class="btn primary" href="#" data-pay="fis1">Comprar agora</a>
          </div>
        </div>
      </article>

      <!-- Curso 3 -->
      <article class="course card">
        <div class="thumb" style="background:linear-gradient(135deg,#f59e0b,#ef4444)"></div>
        <div class="body">
          <h4>Eletromagnetismo — Campos, Circuitos e Aplicações</h4>
          <div class="tags">
            <span class="tag">+30 aulas</span>
            <span class="tag">Mapas conceituais</span>
            <span class="tag">Exercícios comentados</span>
          </div>
          <p class="muted">Fundamentos de eletrostática, magnetostática, Maxwell e aplicações em engenharia.</p>
          <div class="price"><strong>R$ 127</strong> <span class="muted">à vista</span></div>
          <div class="buy">
            <a class="btn" href="#" data-checkout="emag">Ver currículo</a>
            <a class="btn primary" href="#" data-pay="emag">Comprar agora</a>
          </div>
        </div>
      </article>
    </div>

    <p class="muted" style="margin-top:14px">💡 Dica: você pode vender em pacotes (combo Cálculo + Física) com cupom de desconto.</p>
  </div>
</section>

<section id="depoimentos">
  <div class="wrap">
    <h3>⭐ Depoimentos</h3>
    <p class="lead">Resultados de alunos que seguiram o método passo a passo.</p>
    <div class="quotes">
      <div class="card quote"><p>“Explica de forma clara e objetiva. Passei direto em Cálculo I.”</p><div class="who"><div class="avatar"></div><small>Ana Paula • Eng. Mecânica</small></div></div>
      <div class="card quote"><p>“Os PDFs e listas resolvidas salvam tempo demais.”</p><div class="who"><div class="avatar"></div><small>Rafael • Física</small></div></div>
      <div class="card quote"><p>“Didática excelente, com foco no que realmente cai.”</p><div class="who"><div class="avatar"></div><small>Bianca • Eng. Elétrica</small></div></div>
    </div>
  </div>
</section>

<section id="faq" class="faq">
  <div class="wrap">
    <h3>❓ FAQ</h3>
    <details open>
      <summary>Como recebo acesso após o pagamento?</summary>
      <small>Você recebe automaticamente por e-mail o link da área de membros e sua senha. O acesso é pessoal e intransferível.</small>
    </details>
    <details>
      <summary>Os vídeos podem ser baixados?</summary>
      <small>Os vídeos ficam protegidos em plataforma segura (ex.: Vimeo) com acesso via login. O download é bloqueado.</small>
    </details>
    <details>
      <summary>Quais são as formas de pagamento?</summary>
      <small>Cartão de crédito, PIX e boleto, via Mercado Pago/Stripe. Parcelamento disponível.</small>
    </details>
    <details>
      <summary>Existe garantia?</summary>
      <small>Sim, 7 dias de garantia incondicional. Se não gostar, devolvemos seu dinheiro.</small>
    </details>
  </div>
</section>

<section id="contato">
  <div class="wrap">
    <h3>📞 Contato</h3>
    <p class="lead">Ficou com dúvida? Fale comigo e receba orientação para escolher o curso ideal.</p>
    <div class="contact">
      <form class="card" id="contact-form" onsubmit="sendMsg(event)">
        <div style="padding:16px">
          <label for="name">Nome</label>
          <input id="name" name="name" placeholder="Seu nome" required />
          <div style="height:10px"></div>
          <label for="email">E-mail</label>
          <input id="email" name="email" type="email" placeholder="voce@email.com" required />
          <div style="height:10px"></div>
          <label for="msg">Mensagem</label>
          <textarea id="msg" name="msg" placeholder="Escreva sua pergunta..."></textarea>
          <div style="height:14px"></div>
          <button class="btn primary" type="submit">Enviar mensagem</button>
          <p id="sent" class="muted" style="display:none;margin-top:10px">✅ Mensagem preparada no WhatsApp. Clique para enviar.</p>
        </div>
      </form>

      <div class="card" style="padding:16px">
        <h4>Atendimento</h4>
        <p class="muted">WhatsApp: <a href="https://wa.me/5581997993513" target="_blank" rel="noopener">(81) 99799-3513</a><br>E-mail: <a href="mailto:lucas.nsoares@ufpe.br">lucas.nsoares@ufpe.br</a></p>
        <p class="muted">Horário: Seg a Sex, 9h–18h (BRT)</p>
        <hr style="border:0;border-top:1px solid var(--stroke)">
        <h4>Área do Aluno</h4>
        <p class="muted">Após a compra, você receberá o link e a senha de acesso por e-mail automaticamente.</p>
      </div>
    </div>
  </div>
</section>

  </main>  <footer>
    <div class="wrap">
      <p>© <span id="year"></span> Lucas do Nascimento Soares — Todos os direitos reservados.</p>
    </div>
  </footer>  <script>
    // Atualiza ano no rodapé
    document.getElementById('year').textContent = new Date().getFullYear();

    // Checkout: substitua as URLs abaixo por links reais do seu gateway (Mercado Pago/Stripe/Hotmart)
    const PAY_LINKS = {
      calc1: {
        checkout: '#', // página interna do currículo (pode virar /curriculo/calculo1.html)
        pay: 'https://www.mercadopago.com.br/checkout/v1/redirect?pref_id=SEU_ID_CALC1'
      },
      fis1: {
        checkout: '#',
        pay: 'https://www.mercadopago.com.br/checkout/v1/redirect?pref_id=SEU_ID_FIS1'
      },
      emag: {
        checkout: '#',
        pay: 'https://www.mercadopago.com.br/checkout/v1/redirect?pref_id=SEU_ID_EMAG'
      }
    };

    document.querySelectorAll('[data-checkout]').forEach(btn=>{
      btn.addEventListener('click', e=>{
        e.preventDefault();
        const id = btn.getAttribute('data-checkout');
        const url = PAY_LINKS[id]?.checkout || '#';
        if(url==='#') alert('Currículo do curso em breve.');
        else window.location.href = url;
      })
    })

    document.querySelectorAll('[data-pay]').forEach(btn=>{
      btn.addEventListener('click', e=>{
        e.preventDefault();
        const id = btn.getAttribute('data-pay');
        const url = PAY_LINKS[id]?.pay || '#';
        if(url==='#') alert('Link de pagamento não configurado. Edite o arquivo e insira seu link do Mercado Pago/Stripe.');
        else window.open(url,'_blank');
      })
    })

    // Formulário: abre WhatsApp com mensagem pronta
    function sendMsg(ev){
      ev.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const msg = document.getElementById('msg').value.trim();
      const text = encodeURIComponent(`Olá, sou ${name} (email: ${email}). Gostaria de informações sobre os cursos. Mensagem: ${msg}`);
      const wa = `https://wa.me/5581997993513?text=${text}`;
      window.open(wa,'_blank');
      document.getElementById('sent').style.display='block';
    }
  </script></body>
</html>
