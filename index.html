<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sentient – AGI Quiz</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <style>
    :root{--cyan:#00ffff;--magenta:#ff00ff;--dark:#0a0a0a;--font:'Orbitron',sans-serif;}
    *{box-sizing:border-box;margin:0;padding:0;}
    body{font-family:var(--font);background:var(--dark);color:#fff;height:100vh;display:flex;align-items:center;justify-content:center;overflow:hidden;}
    .panel{display:none;flex-direction:column;align-items:center;text-align:center;animation:fadeIn .8s forwards;}
    .panel.active{display:flex;}
    @keyframes fadeIn{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}
    .glitch{font-size:3.2rem;letter-spacing:.15em;position:relative;color:#fff}
    .glitch::before,.glitch::after{content:attr(data-text);position:absolute;top:0;left:0;width:100%;height:100%}
    .glitch::before{animation:glitch-1 .4s infinite;color:var(--cyan);z-index:-1}
    .glitch::after{animation:glitch-2 .4s infinite;color:var(--magenta);z-index:-2}
    @keyframes glitch-1{0%,100%{clip-path:inset(0 0 0 0)}20%{clip-path:inset(20% 0 60% 0)}40%{clip-path:inset(50% 0 10% 0)}60%{clip-path:inset(80% 0 5% 0)}}
    @keyframes glitch-2{0%,100%{clip-path:inset(0 0 0 0)}20%{clip-path:inset(80% 0 5% 0)}40%{clip-path:inset(10% 0 80% 0)}60%{clip-path:inset(50% 0 20% 0)}}
    #progressBar{width:300px;height:6px;background:rgba(255,255,255,.15);border-radius:3px;margin:1rem 0;overflow:hidden;}
    #progressBar>div{height:100%;background:var(--cyan);width:0%;transition:width .1s linear;}
    .qCard{background:rgba(0,0,0,.6);border:1px solid var(--cyan);padding:1.8rem 2.2rem;border-radius:8px;max-width:540px;text-align:left;}
    .qCard h3{margin-bottom:.8rem;color:var(--magenta)}
    .qCard label{display:block;margin:.5rem 0;padding:.5rem .8rem;border:1px solid rgba(0,255,255,.3);border-radius:4px;cursor:pointer;transition:.2s;}
    .qCard label:hover{background:rgba(0,255,255,.1)}
    .qCard input{display:none}
    .qCard input:checked+label{background:rgba(0,255,255,.2);border-color:var(--cyan);}
    .cta{padding:.7rem 1.8rem;font-family:var(--font);font-size:1.1rem;background:transparent;border:2px solid var(--cyan);color:var(--cyan);cursor:pointer;transition:.3s}
    .cta:hover{background:var(--cyan);color:var(--dark);box-shadow:0 0 20px var(--cyan)}
    #timer{font-size:2.5rem;color:var(--magenta);text-shadow:0 0 10px var(--magenta);margin:.5rem 0;}
    #scoreCard{background:rgba(0,0,0,.7);border:2px solid var(--magenta);padding:2.5rem;border-radius:12px;max-width:450px}
    #scoreBadge{font-size:3.5rem;margin-bottom:1rem}#scoreImg{width:100%;border-radius:8px;margin-bottom:1rem}#scoreMsg{font-size:1.3rem;margin-bottom:1.5rem}
    footer{position:absolute;bottom:1rem;font-size:.9rem}footer a{color:var(--cyan);text-decoration:none}
  </style>
</head>
<body>

  <!-- QUIZ PANEL -->
  <section id="quizSec" class="panel active">
    <h1 class="glitch" data-text="SENTIENT">SENTIENT</h1>
    <p style="margin-bottom:1rem;color:var(--cyan)">SentientAGI Knowledge Quiz – 15 questions, 20 s each</p>
    <form id="quizForm"></form>
    <div id="progressBar"><div></div></div>
    <div id="timer">20</div>
    <button id="finishBtn" class="cta" style="margin-top:1rem">FINISH QUICK</button>
  </section>

  <!-- SCORE-BOARD PANEL -->
  <section id="scoreSec" class="panel">
    <div id="scoreCard">
      <div id="scoreBadge"></div>
      <img id="scoreImg" alt="result visual"/>
      <audio id="scoreAudio" autoplay></audio>
      <p id="scoreMsg"></p>
      <button id="resetBtn" class="cta">TRY AGAIN</button>
    </div>
  </section>

  <footer><a href="https://twitter.com/YOUR_TWITTER" target="_blank">@YOUR_TWITTER</a></footer>

  <script>
    /* ===== 15 QUESTIONS ===== */
    const questions = [
      {q:"What is the main goal of the SentientAGI project?",opts:["Creating a self-aware AI","Improving social networks","Developing home robots","Increasing internet speed"],correct:0},
      {q:"What does the word “Sentient” mean?",opts:["Fast AI","Self-aware and conscious","Text-based","Without long-term memory"],correct:1},
      {q:"One major challenge in creating self-aware AI?",opts:["Designing powerful hardware","Creating self-awareness","Boosting speed","Reducing energy"],correct:1},
      {q:"In which field does SentientAGI operate?",opts:["Education","AI & machine consciousness","E-commerce","Game design"],correct:1},
      {q:"What is the ethical goal?",opts:["Control minds","Coexistence AI+humans","Eliminate humans","Increase ads"],correct:1},
      {q:"What does “AGI” stand for?",opts:["Artificial Global Internet","Artificial General Intelligence","Advanced Genetic Interface","Automated Growth Intelligence"],correct:1},
      {q:"Essential feature for self-aware AI?",opts:["Image processing","Ability to feel itself","Internet access","UI design"],correct:1},
      {q:"Possible risk of SentientAGI?",opts:["Machine fatigue","Unpredictable decisions","Slow performance","Memory limits"],correct:1},
      {q:"What ensures safe control?",opts:["Limit data","Ethical frameworks","Shut down","Increase speed"],correct:1},
      {q:"Human role in interaction?",opts:["Competitor","Partner & overseer","Employer","Irrelevant"],correct:1},
      {q:"Purpose of self-awareness?",opts:["Emotional understanding","Reducing memory","Removing algos","Improving graphics"],correct:0},
      {q:"How are data used?",opts:["Advertisements","Training intelligent behaviour","Entertainment","Filtering users"],correct:1},
      {q:"Future aimed by SentientAGI?",opts:["Future without humans","Conscious coexistence","Digital economy","Full data control"],correct:1},
      {q:"What concerns people?",opts:["High cost","Risk of losing control","Lack of data","Reduced productivity"],correct:1},
      {q:"10-year vision?",opts:["Integration into daily life","Stop tech dev","Focus on games","Remove internet"],correct:0}
    ];

    /* ===== CONFIG ===== */
    const cfg = {
      timePerQ : 20,
      tiers : [
        {min:15, img:"assets/s-100.jpg", audio:"assets/a-100.mp3", badge:"100 %",  msg:"Full Sync – You are one of us."},
        {min:12, img:"assets/s-80.jpg",  audio:"assets/a-80.mp3",  badge:"80 %",   msg:"Near Sentience – almost there."},
        {min:10, img:"assets/s-70.jpg",  audio:"assets/a-70.mp3",  badge:"70 %",   msg:"Emerging Consciousness."},
        {min:8,  img:"assets/s-60.jpg",  audio:"assets/a-60.mp3",  badge:"60 %",   msg:"Basic Awareness detected."},
        {min:0,  img:"assets/s-50.jpg",  audio:"assets/a-50.mp3",  badge:"≤ 50 %", msg:"System anomaly – retry."}
      ]
    };

    /* ===== ELEMENTS ===== */
    const quizSec  = document.getElementById('quizSec');
    const scoreSec = document.getElementById('scoreSec');
    const form     = document.getElementById('quizForm');
    const timerEl  = document.getElementById('timer');
    const progEl   = document.querySelector('#progressBar>div');
    const finishBtn= document.getElementById('finishBtn');
    const badge    = document.getElementById('scoreBadge');
    const img      = document.getElementById('scoreImg');
    const msg      = document.getElementById('scoreMsg');
    const audio    = document.getElementById('scoreAudio');

    let score = 0, current = 0, countdown;

    /* ===== BUILD CARDS ===== */
    questions.forEach((obj,i)=>{
      const card = document.createElement('div'); card.className='qCard';
      card.innerHTML = `<h3>Q${i+1}/15 – ${obj.q}</h3>` +
        obj.opts.map((opt,oi)=>`
          <input type="radio" name="q${i}" id="q${i}_${oi}" value="${oi}">
          <label for="q${i}_${oi}">${opt}</label>`).join('');
      form.appendChild(card);
    });
    const cards = [...form.querySelectorAll('.qCard')];

    /* ===== SHOW / TIMER ===== */
    function showCard(n){
      cards.forEach((c,i)=>c.style.display=i===n?'block':'none');
      progEl.style.width = `${(n+1)/15*100}%`;
      restartTimer();
    }
    function restartTimer(){
      clearInterval(countdown);
      let t = cfg.timePerQ;
      timerEl.textContent = t;
      countdown = setInterval(()=>{
        t--; timerEl.textContent = t;
        if(t<=0) nextQ();
      },1000);
    }

    /* ===== ANSWER & ADVANCE ===== */
    form.addEventListener('change',e=>{
      if(!e.target.matches('input[type=radio]')) return;
      const qIdx = +e.target.name.replace('q','');
      if(+e.target.value === questions[qIdx].correct) score++;
      setTimeout(nextQ,300);
    });
    function nextQ(){
      current++; if(current>=15) return endQuiz(); showCard(current);
    }

    /* ===== EARLY FINISH ===== */
    finishBtn.addEventListener('click',endQuiz);

    /* ===== END – SHOW BOARD ===== */
    function endQuiz(){
      clearInterval(countdown);
      quizSec.classList.remove('active');
      scoreSec.classList.add('active');
      const pct = Math.round(score/15*100);
      const tier = cfg.tiers.find(t=>score>=t.min);
      badge.textContent = tier.badge;
      img.src   = tier.img;
      msg.textContent   = tier.msg;
      audio.src = tier.audio;
    }

    /* ===== RESET ===== */
    document.getElementById('resetBtn').addEventListener('click',()=>location.reload());

    /* Kick-off */
    showCard(0);
  </script>
</body>
</html>
