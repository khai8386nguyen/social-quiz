const questions = [
    {
      title: "Q1 — You enter the shop...",
      text: "The menu board lights up with over 40 different flavours. What's your first instinct?",
      options: [
        { text: "\u201cLet's just pick something new!\u201d", scores: { doer: 2 } },
        { text: "Already researched the menu before coming.", scores: { planner: 2 } },
        { text: "Struggling to decide for 15 mins on what to order.", scores: { thinker: 2 } },
        { text: "Immediately lock onto the same flavour you always order.", scores: { laser: 2 } }
      ]
    },
    {
      title: "Q2 — The queue suddenly becomes really long.",
      text: "What do you do?",
      options: [
        { text: "Jump into whichever queue looks shortest.", scores: { doer: 2 } },
        { text: "Stay in the same queue no matter what.", scores: { follow: 2 } },
        { text: "Keep switching to the \u201cfaster\u201d queue.", scores: { thinker: 2 } },
        { text: "Notice yourself getting impatient.", scores: { storm: 2 } }
      ]
    },
    {
      title: "Q3 — While waiting...",
      text: "You notice a magical \u201cCreate Your Own Flavour\u201d machine.",
      options: [
        { text: "Lose track of time creating the perfect flavour.", scores: { laser: 2 } },
        { text: "Spend ten minutes finding the perfect recipe before starting.", scores: { planner: 2 } },
        { text: "Think back to all the flavours you've enjoyed before.", scores: { thinker: 2 } }
      ]
    },
    {
      title: "Q4 — When you turn around, you see a magical red door…",
      text: "What do you do?",
      options: [
        { text: "Ask around before opening the door.", scores: { thinker: 1, planner: 1 } },
        { text: "Decide to just open the door and see for yourself.", scores: { doer: 2 } },
        { text: "Ignore it and head to the cashier.", scores: { follow: 2 } },
        { text: "Feeling anxious, \u201cI wonder what might be behind it…\u201d", scores: { storm: 2 } }
      ]
    },
    {
      title: "Q5 — The red door opens to reveal a magical toppings station.",
      text: "You see 2 routes you can take…",
      options: [
        { text: "Route A - The Safe Bet, familiar favourites.", scores: { planner: 2 } },
        { text: "Route B - Mystery Toppings, surprise me!", scores: { doer: 2 } },
        { text: "Stuck at the crossroads because you can't decide.", scores: { thinker: 2 } }
      ]
    },
    {
      title: "Q6 — Oh no...",
      text: "Your favourite topping just ran out! What do you do?",
      options: [
        { text: "Pick another topping and keep moving.", scores: { follow: 2 } },
        { text: "Feeling disappointed, as it was your favourite.", scores: { storm: 1, laser: 1 } },
        { text: "\u201cThat wasn't part of the plan…\u201d Finds the closest substitute.", scores: { planner: 2 } },
        { text: "Take so long comparing alternatives that multiple people get their froyo first.", scores: { thinker: 2 } }
      ]
    },
    {
      title: "Q7 — You accidentally spill some toppings.",
      text: "What happens next?",
      options: [
        { text: "Feel really guilty and embarrassed for making a mess.", scores: { storm: 2 } },
        { text: "You don't notice the spill because you're so fixated on reaching the cashier.", scores: { laser: 2 } },
        { text: "Clean it up and keep going.", scores: { follow: 2 } }
      ]
    },
    {
      title: "Q8 — The cashier asks...",
      text: "\u201cWould you like to try today's mystery topping?\u201d",
      options: [
        { text: "Nope, I'm happy with what I have!", scores: { follow: 1, laser: 1 } },
        { text: "Yes! It sounds exciting.", scores: { storm: 1, doer: 1 } },
        { text: "Ask fifteen follow-up questions about the topping before deciding.", scores: { thinker: 2 } },
        { text: "Nope, I don't like being surprised. What if I don't like it?", scores: { planner: 2 } }
      ]
    },
    {
      title: "Q9 — After paying, you try to find a seat.",
      text: "The whole place is completely packed!",
      options: [
        { text: "Feel overwhelmed and frustrated that there are no seats.", scores: { storm: 2 } },
        { text: "Choose one seat closest to the window and wait for it.", scores: { laser: 2 } },
        { text: "Look around before deciding whether to wait or head home.", scores: { planner: 2 } },
        { text: "Leave the store and walk home while eating.", scores: { follow: 1, doer: 1 } }
      ]
    },
    {
      title: "Q10 — Before you leave, the staff asks you…",
      text: "\u201cWhat's the BEST part of building your froyo?\u201d",
      options: [
        { text: "Being spontaneous and trying something new!", scores: { doer: 2 } },
        { text: "Discovering what I like in my froyo!", scores: { thinker: 2 } },
        { text: "Planning and crafting out a perfect combo of yogurt and topping!", scores: { planner: 2 } },
        { text: "Finally seeing it all come together makes it worth it!", scores: { follow: 2 } },
        { text: "How happy it made me feel!", scores: { storm: 2 } },
        { text: "I loved getting completely absorbed in the process!", scores: { laser: 2 } }
      ]
    }
  ];

  const resultData = {
    doer: {
      label: "The Doer",
      flavour: "Rainbow Rush",
      badgeBg: "#FAEEDA", badgeColor: "#633806",
      desc: "You leap before you look, in the best way. Life's too short to overthink the toppings, so you dive in, try new things, and trust your gut. Bold, bright, and full of surprises, just like your flavour."
    },
    planner: {
      label: "The Planner",
      flavour: "Honey Granola Bliss",
      badgeBg: "#F3E5D0", badgeColor: "#6B4423",
      desc: "You like to know what you're getting into, and that's not a bad thing. You do your research, weigh your options, and build something reliably delicious. Wholesome, grounded, and always prepared."
    },
    thinker: {
      label: "The Thinker",
      flavour: "Matcha Bloom",
      badgeBg: "#E1F5EE", badgeColor: "#085041",
      desc: "You take your time because the details matter to you. Every decision gets turned over in your mind before you commit, and that thoughtfulness is your strength. Calm, considered, and quietly deep."
    },
    laser: {
      label: "The Laser",
      flavour: "Triple Chocolate Crunch",
      badgeBg: "#E8DED9", badgeColor: "#4A2E1F",
      desc: "Once you're locked in, nothing else exists. You get so absorbed in what you're doing that the world fades into the background. Rich, intense, and impossible to distract."
    },
    follow: {
      label: "Follow Through",
      flavour: "Salted Caramel Crunch",
      badgeBg: "#EEEDFE", badgeColor: "#3C3489",
      desc: "You don't need everything to go perfectly, you just need to keep moving. When plans change, you adapt, adjust, and get it done. Steady, dependable, with just the right amount of edge."
    },
    storm: {
      label: "The Storm",
      flavour: "Berry Burst",
      badgeBg: "#FCE4EC", badgeColor: "#8E2450",
      desc: "You feel things fully, and you're not afraid to show it. Frustration, excitement, joy, it all comes through in bursts of energy. Vivid, expressive, and impossible to ignore."
    }
  };

  const styleOrder = ["doer", "planner", "thinker", "laser", "follow", "storm"];

  let current = 0, scores = {}, selected = null, history = [];

  function resetScores() {
    scores = { doer: 0, planner: 0, thinker: 0, laser: 0, follow: 0, storm: 0 };
  }

  function show(id) {
    document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }

  function startQuiz() { current = 0; resetScores(); history = []; renderQ(); show('screen-quiz'); }

  function renderQ() {
    const q = questions[current];
    const dots = document.getElementById('q-dots');
    dots.innerHTML = '';
    for (let i = 0; i < questions.length; i++) {
      const d = document.createElement('div');
      d.className = 'dot' + (i < current ? ' done' : i === current ? ' active' : '');
      dots.appendChild(d);
    }
    document.getElementById('q-title').textContent = q.title;
    document.getElementById('q-text').textContent = q.text;
    const prevIdx = history[current];
    document.getElementById('q-options').innerHTML = q.options.map((o,i) =>
      `<button class="opt${prevIdx === i ? ' selected' : ''}" onclick="pick(${i})">${o.text}</button>`
    ).join('');
    document.getElementById('back-btn').style.display = current > 0 ? 'flex' : 'none';
    selected = null;
  }

  function pick(idx) {
    selected = idx;
    document.querySelectorAll('.opt').forEach((b,i) => b.classList.toggle('selected', i===idx));
    const o = questions[current].options[idx];
    for (const key in o.scores) { scores[key] += o.scores[key]; }
    history[current] = idx;
    current++;
    setTimeout(() => {
      if (current < questions.length) { renderQ(); }
      else { showResult(); }
    }, 300);
  }

  function goBack() {
    if (current <= 0) return;
    current--;
    const prevIdx = history[current];
    if (prevIdx !== undefined) {
      const o = questions[current].options[prevIdx];
      for (const key in o.scores) { scores[key] -= o.scores[key]; }
    }
    renderQ();
  }

  function showResult() {
    let winner = styleOrder[0];
    for (const key of styleOrder) {
      if (scores[key] > scores[winner]) winner = key;
    }
    const r = resultData[winner];

    document.getElementById('result-badge').textContent = r.label;
    document.getElementById('result-badge').style.background = r.badgeBg;
    document.getElementById('result-badge').style.color = r.badgeColor;
    document.getElementById('result-type').textContent = r.flavour;
    document.getElementById('result-desc').textContent = r.desc;
    document.getElementById('share-toast').style.display = 'none';

    show('screen-result');

    const total = styleOrder.reduce((sum, key) => sum + scores[key], 0) || 1;
    setTimeout(() => {
      styleOrder.forEach(key => {
        const pct = Math.round(scores[key] / total * 100);
        document.getElementById('bar-' + key).style.width = pct + '%';
        document.getElementById('pct-' + key).textContent = pct + '%';
      });
    }, 100);
  }

  function restart() { current = 0; resetScores(); history = []; renderQ(); show('screen-quiz'); }

  function shareResult() {
    const flavour = document.getElementById('result-type').textContent;
    const style = document.getElementById('result-badge').textContent;
    navigator.clipboard.writeText(style + ' — ' + flavour + ' — take the quiz: ' + window.location.href).then(() => {
      const t = document.getElementById('share-toast');
      t.style.display = 'block';
      setTimeout(() => t.style.display = 'none', 2500);
    });
  }
