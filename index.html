<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#0b1420">
<title>IP Lab | Laboratório de Redes</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600&family=Sora:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#0b1420;--panel:#101d2e;--line:#1e3350;--ink:#e6f0fb;--mute:#8ea6c2;--blue:#2f8cff;--cyan:#36d1ff;--ok:#3ddc97;--bad:#ff6b7a;
--sans:'Sora',system-ui,sans-serif;--mono:'JetBrains Mono',ui-monospace,monospace}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--ink);font:16px/1.6 var(--sans);padding:0 18px}
main{max-width:820px;margin:0 auto}
section{padding:44px 0;border-top:1px solid var(--line)}
h1{font-size:clamp(2rem,7vw,3.2rem);line-height:1.1;margin:10px 0 14px}
h2{font-size:1.5rem;margin-bottom:8px}
p{color:var(--mute);max-width:62ch}
.logo{font-family:var(--mono);font-weight:600;color:var(--cyan);font-size:1.1rem;padding-top:22px}
.logo i{font-style:normal;animation:blink 1s steps(1) infinite}
@keyframes blink{50%{opacity:0}}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px;margin-top:18px}
button{font:600 .95rem var(--sans);background:var(--blue);color:#fff;border:0;border-radius:8px;padding:11px 18px;cursor:pointer}
button:hover:not(:disabled){background:#4b9dff}
button:disabled{background:#223552;color:#6f86a3;cursor:not-allowed}
button.ghost{background:transparent;border:1px solid var(--line);color:var(--ink)}
:focus-visible{outline:2px solid var(--cyan);outline-offset:2px}
.mono{font-family:var(--mono)}
.row{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
label.chk{display:flex;gap:10px;align-items:flex-start;color:var(--mute);font-size:.9rem;margin-bottom:14px}
label.chk input{margin-top:5px;accent-color:var(--blue)}
.res{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:16px}
.res div{background:var(--bg);border:1px solid var(--line);border-radius:8px;padding:12px;min-width:0}
.res small{color:var(--mute);display:block}
.res b{font:600 1rem var(--mono);word-break:break-all;color:var(--cyan)}
.hint{font-size:.85rem;color:var(--mute);margin-top:8px}
/* viagem */
.path{display:flex;justify-content:space-between;gap:6px;margin:22px 0 14px;position:relative}
.node{flex:1;text-align:center;font-size:.78rem;color:var(--mute);position:relative;z-index:1}
.node span{display:grid;place-items:center;width:48px;height:48px;margin:0 auto 6px;border-radius:50%;background:var(--bg);border:2px solid var(--line);font-size:1.3rem;transition:.35s}
.node.on span{border-color:var(--cyan);box-shadow:0 0 18px rgba(54,209,255,.55);transform:scale(1.12)}
.node.on{color:var(--ink)}
.path:before{content:"";position:absolute;left:8%;right:8%;top:24px;height:2px;background:var(--line)}
.bar{position:absolute;left:8%;top:24px;height:2px;background:var(--cyan);width:0;transition:width .6s}
#cap{min-height:3.4em;color:var(--ink)}
@media(max-width:560px){.path{flex-direction:column;gap:14px;align-items:stretch}.path:before,.bar{display:none}.node{display:flex;gap:12px;align-items:center;text-align:left}.node span{margin:0;flex:none}}
/* analisador */
input[type=text]{flex:1;min-width:180px;background:var(--bg);border:1px solid var(--line);color:var(--ink);border-radius:8px;padding:11px 14px;font:1rem var(--mono)}
.tag{display:inline-block;padding:2px 10px;border-radius:99px;font-size:.85rem;font-weight:600;margin-bottom:8px}
.tag.pub{background:rgba(61,220,151,.15);color:var(--ok)}.tag.priv{background:rgba(47,140,255,.18);color:var(--cyan)}.tag.bad{background:rgba(255,107,122,.15);color:var(--bad)}
#bin{font:.95rem var(--mono);color:var(--cyan);word-break:break-all;margin-top:8px}
/* quiz */
.opt{display:block;width:100%;text-align:left;margin-top:10px;background:var(--bg);border:1px solid var(--line);color:var(--ink);font-weight:400}
.opt.right{border-color:var(--ok);background:rgba(61,220,151,.12)}
.opt.wrong{border-color:var(--bad);background:rgba(255,107,122,.12)}
#why{margin-top:12px;color:var(--ink)}
.know{display:grid;gap:14px;margin-top:16px}
.know code{font:600 1rem var(--mono);color:var(--cyan)}
footer{padding:30px 0 40px;border-top:1px solid var(--line);font-size:.85rem;color:var(--mute)}
@media(prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style>
</head>
<body>
<main>
<div class="logo">IP LAB<i>_</i></div>

<header style="padding:30px 0 44px">
<h1>Conheça sua conexão.</h1>
<p>Consulte seus IPs, veja o caminho de um pacote pela internet, analise qualquer endereço e teste o que aprendeu.</p>
</header>

<section id="diag">
<h2>Diagnóstico de rede</h2>
<p>Mostra os endereços públicos IPv4 e IPv6 que sua conexão usa.</p>
<div class="card">
<label class="chk"><input type="checkbox" id="ok"><span>Estou ciente de que a consulta usa serviços externos e que meu endereço IP será consultado.</span></label>
<div class="row"><button id="go" disabled>Iniciar diagnóstico</button><button id="copy" class="ghost" disabled>Copiar IPv4</button></div>
<p class="hint" id="h">Marque a caixa acima para liberar o botão.</p>
<div class="res"><div><small>IPv4</small><b id="v4">Aguardando consulta</b></div><div><small>IPv6</small><b id="v6">Aguardando consulta</b></div></div>
</div>
</section>

<section id="viagem">
<h2>A viagem do pacote</h2>
<p>O que acontece quando você abre um site? Clique e acompanhe.</p>
<div class="card">
<div class="path" id="path">
<div class="bar" id="bar"></div>
<div class="node"><span>📱</span>Seu celular</div>
<div class="node"><span>📡</span>Roteador</div>
<div class="node"><span>🏢</span>Provedor</div>
<div class="node"><span>📖</span>DNS</div>
<div class="node"><span>🖥️</span>Servidor</div>
</div>
<p id="cap">Clique em “Enviar pacote” para começar.</p>
<div class="row" style="margin-top:12px"><button id="send">Enviar pacote</button></div>
</div>
</section>

<section id="analisador">
<h2>Analisador de IP</h2>
<p>Digite um endereço e descubra o que ele é. Tudo roda no seu navegador, nada é enviado.</p>
<div class="card">
<div class="row"><input type="text" id="ip" placeholder="Ex.: 192.168.1.1" aria-label="Endereço IP" autocomplete="off" inputmode="text"><button id="an">Analisar</button></div>
<div id="out" style="margin-top:14px"></div>
</div>
</section>

<section id="quiz">
<h2>Mini quiz</h2>
<p>Cinco perguntas rápidas sobre o que você viu aqui.</p>
<div class="card" id="qz"></div>
</section>

<section id="base">
<h2>Fundamentos de rede</h2>
<div class="know">
<div><code>IPv4 · 192.168.1.1</code><p>Quarta versão do Protocolo de Internet. Usa 32 bits, o que dá cerca de 4,3 bilhões de endereços.</p></div>
<div><code>IPv6 · 2001:db8::1</code><p>Versão mais nova, com 128 bits. Tem endereços de sobra para todos os dispositivos conectados.</p></div>
<div><code>DNS · google.com → IP</code><p>O Domain Name System traduz nomes de sites em endereços IP, para você não precisar decorar números.</p></div>
<div><code>Dual Stack</code><p>Configuração que usa IPv4 e IPv6 ao mesmo tempo, para falar com qualquer serviço.</p></div>
</div>
</section>

<footer>
<p><b>Privacidade:</b> esta página mostra os endereços devolvidos pelos serviços de consulta e não guarda nada em banco de dados próprio. Os serviços externos podem registrar a requisição.</p>
<p style="margin-top:10px">IP LAB_ · projeto educativo de redes · versão 3.0 · 2026</p>
</footer>
</main>

<script>
const $=id=>document.getElementById(id);

/* ---- diagnóstico ---- */
const ok=$('ok'),go=$('go'),cp=$('copy');
ok.onchange=()=>{go.disabled=!ok.checked;$('h').textContent=ok.checked?'Pronto! Pode iniciar.':'Marque a caixa acima para liberar o botão.'};
async function get(url){const c=new AbortController();const t=setTimeout(()=>c.abort(),6000);
 try{const r=await fetch(url,{signal:c.signal});return (await r.json()).ip}catch(e){return null}finally{clearTimeout(t)}}
go.onclick=async()=>{
 go.disabled=true;$('v4').textContent='Consultando...';$('v6').textContent='Consultando...';
 const [a,b]=await Promise.all([get('https://api.ipify.org?format=json'),get('https://api6.ipify.org?format=json')]);
 $('v4').textContent=a||'Não foi possível obter';
 $('v6').textContent=b||'Sua conexão não usa IPv6 (ou a consulta falhou)';
 cp.disabled=!a;go.disabled=false;
 $('h').textContent=b?'Sua conexão tem IPv4 e IPv6: é Dual Stack!':'Só IPv4 encontrado. Isso é bem comum em redes móveis e domésticas.';
};
cp.onclick=async()=>{try{await navigator.clipboard.writeText($('v4').textContent);cp.textContent='Copiado!'}catch(e){cp.textContent='Copie manualmente'}setTimeout(()=>cp.textContent='Copiar IPv4',1800)};

/* ---- viagem do pacote ---- */
const nodes=[...document.querySelectorAll('.node')],bar=$('bar');
const steps=[
 [0,'Seu celular monta o pedido: “quero o site exemplo.com”. Ele ainda não sabe o endereço IP desse site.'],
 [1,'O pedido sai do celular e chega ao roteador de casa. Ele usa NAT: troca seu IP privado (192.168.x.x) pelo IP público da sua conexão.'],
 [2,'O provedor de internet recebe o pacote e decide por quais caminhos ele segue pela rede.'],
 [3,'O servidor DNS responde: “exemplo.com é 93.184.216.34”. Agora o pacote sabe para onde ir.'],
 [4,'O servidor recebe o pedido, prepara a página e devolve a resposta pelo mesmo caminho. Tudo em milissegundos!']
];
let busy=false;
$('send').onclick=async()=>{
 if(busy)return;busy=true;$('send').disabled=true;
 for(let i=0;i<steps.length;i++){
  nodes.forEach((n,k)=>n.classList.toggle('on',k===steps[i][0]));
  bar.style.width=(steps[i][0]/4*84)+'%';$('cap').textContent=steps[i][1];
  await new Promise(r=>setTimeout(r,2600));
 }
 busy=false;$('send').disabled=false;$('send').textContent='Enviar de novo';
};

/* ---- analisador ---- */
const oct=s=>s.split('.').map(Number);
function an4(s){
 const p=s.split('.');
 if(p.length!==4||p.some(x=>!/^\d{1,3}$/.test(x)||+x>255))return null;
 const [a,b]=oct(s);let t,c,w;
 if(a===10||(a===172&&b>=16&&b<=31)||(a===192&&b===168)){t='priv';c='Privado';w='Faixa reservada para redes locais (casa, escola, empresa). Não é roteado na internet: seu roteador usa NAT para traduzir.'}
 else if(a===127){t='priv';c='Loopback';w='Aponta para o próprio aparelho. Serve para testes locais.'}
 else if(a===169&&b===254){t='priv';c='Link-local';w='Endereço automático usado quando o aparelho não recebeu IP do roteador (DHCP falhou).'}
 else if(a===100&&b>=64&&b<=127){t='priv';c='CGNAT';w='Faixa que provedores usam para compartilhar um mesmo IP público entre vários clientes.'}
 else if(a===0){t='bad';c='Reservado';w='O bloco 0.0.0.0/8 significa “esta rede” e não identifica um aparelho.'}
 else if(a>=224&&a<=239){t='bad';c='Multicast';w='Usado para enviar dados a um grupo de aparelhos de uma vez.'}
 else if(a>=240){t='bad';c='Reservado';w='Faixa reservada para usos futuros e especiais.'}
 else{t='pub';c='Público';w='Pode ser roteado na internet. É o tipo de endereço que identifica sua conexão para o mundo.'}
 const cls=a<128?'A':a<192?'B':a<224?'C':'-';
 const bin=oct(s).map(n=>n.toString(2).padStart(8,'0')).join('.');
 return {t,c,w,cls,bin};
}
function an6(s){
 if(!/^[0-9a-f:]+$/i.test(s)||!s.includes(':')||(s.match(/::/g)||[]).length>1||s.split(':').length>8)return null;
 const l=s.toLowerCase();
 if(l==='::1')return {t:'priv',c:'Loopback IPv6',w:'É o “127.0.0.1” do IPv6: aponta para o próprio aparelho.'};
 if(/^fe[89ab]/.test(l))return {t:'priv',c:'Link-local IPv6',w:'Válido apenas dentro da rede local imediata.'};
 if(/^f[cd]/.test(l))return {t:'priv',c:'Local único',w:'Equivalente aos IPs privados do IPv4 (fc00::/7).'};
 if(l.startsWith('2001:db8'))return {t:'bad',c:'Documentação',w:'Faixa reservada para exemplos e livros. Não existe na internet real.'};
 return {t:'pub',c:'Global (público)',w:'Endereço roteável na internet.'};
}
function run(){
 const s=$('ip').value.trim(),o=$('out');
 if(!s){o.innerHTML='<p>Digite um endereço para analisar.</p>';return}
 const r=an4(s)||an6(s);
 if(!r){o.innerHTML='<span class="tag bad">Inválido</span><p>Um IPv4 tem 4 números de 0 a 255 separados por ponto (ex.: 192.168.0.10). Um IPv6 usa grupos hexadecimais separados por dois-pontos.</p>';return}
 o.innerHTML=`<span class="tag ${r.t}">${r.c}</span><p style="color:var(--ink)">${r.w}</p>`+
  (r.bin?`<p class="hint">Classe ${r.cls} · em binário:</p><div id="bin">${r.bin}</div>`:'');
}
$('an').onclick=run;$('ip').onkeydown=e=>{if(e.key==='Enter')run()};

/* ---- quiz ---- */
const Q=[
 ['Quantos bits tem um endereço IPv4?',['32','64','128'],0,'IPv4 usa 32 bits (cerca de 4,3 bilhões de endereços). Quem usa 128 bits é o IPv6.'],
 ['Qual destes é um IP privado?',['8.8.8.8','192.168.0.10','200.10.5.1'],1,'192.168.0.0 a 192.168.255.255 é uma das três faixas privadas (as outras: 10.x.x.x e 172.16 a 172.31).'],
 ['Qual é a função do DNS?',['Proteger contra vírus','Traduzir nomes em IPs','Aumentar a velocidade do Wi-Fi'],1,'O DNS é a “lista telefônica” da internet: transforma google.com em um endereço IP.'],
 ['O que o roteador faz com NAT?',['Troca IP privado por público','Apaga seus dados','Cria sites'],0,'O NAT permite que vários aparelhos da casa compartilhem um único IP público.'],
 ['O que é Dual Stack?',['Duas telas','Usar IPv4 e IPv6 ao mesmo tempo','Dois roteadores'],1,'Dual Stack é ter IPv4 e IPv6 funcionando juntos, para acessar qualquer serviço.']
];
let qi=0,pts=0;
function showQ(){
 const box=$('qz');
 if(qi>=Q.length){box.innerHTML=`<h2 style="margin:0 0 6px">Você acertou ${pts} de ${Q.length}</h2><p>${pts>=4?'Mandou muito bem! Você já entende o básico de redes.':'Boa tentativa! Releia as seções acima e tente de novo.'}</p><div class="row" style="margin-top:14px"><button id="rs">Refazer quiz</button></div>`;
  $('rs').onclick=()=>{qi=0;pts=0;showQ()};return}
 const q=Q[qi];
 box.innerHTML=`<p class="hint">Pergunta ${qi+1} de ${Q.length}</p><h3 style="font-size:1.1rem;margin-top:4px">${q[0]}</h3>`+
  q[1].map((t,i)=>`<button class="opt" data-i="${i}">${t}</button>`).join('')+'<div id="why"></div>';
 box.querySelectorAll('.opt').forEach(b=>b.onclick=()=>{
  const i=+b.dataset.i;box.querySelectorAll('.opt').forEach(x=>x.disabled=true);
  box.querySelectorAll('.opt')[q[2]].classList.add('right');
  if(i===q[2])pts++;else b.classList.add('wrong');
  $('why').innerHTML=`<p style="color:var(--ink)">${q[3]}</p><div class="row" style="margin-top:12px"><button id="nx">${qi===Q.length-1?'Ver resultado':'Próxima'}</button></div>`;
  $('nx').onclick=()=>{qi++;showQ()};
 });
}
showQ();
</script>
</body>
</html>