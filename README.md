<div align="center">

  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/banner.svg" alt="Pixel Pokémon Banner" width="100%">

  <br/>
  
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/divider.svg" alt="Pokéball Divider" width="680">

  <h3>Press START ➜ Level up code, catch new skills, ship rare drops</h3>

</div>

<p align="center">
  <a href="#trainer-card">Trainer Card</a> •
  <a href="#skills">Skills</a> •
  <a href="#gym-badges">Gym Badges</a> •
  <a href="#quest-log">Quest Log</a> •
  <a href="#pokedex-projects">Projects</a> •
  <a href="#stats">Stats</a> •
  <a href="#achievements">Achievements</a> •
  <a href="#contact">Contact</a>
</p>

<p align="center">
  <a href="https://github.com/AsukaFurukawa">
    <img src="https://komarev.com/ghpvc/?username=AsukaFurukawa&style=for-the-badge&label=VISITORS&color=0ea5e9" alt="visitors">
  </a>
  <a href="https://github.com/AsukaFurukawa">
    <img src="https://img.shields.io/badge/Status-Online-brightgreen?style=for-the-badge&logo=github" alt="status">
  </a>
  <a href="https://github.com/AsukaFurukawa">
    <img src="https://img.shields.io/badge/Level-Developer-blue?style=for-the-badge&logo=code" alt="level">
  </a>
</p>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=16&duration=3000&pause=700&color=00E6E6&center=true&vCenter=true&width=800&lines=Hi%2C+I%27m+Prachi+%F0%9F%8E%AF;Full%E2%80%91stack+%E2%80%A2+ML+%E2%80%A2+Data+Viz;Catching+bugs+%E2%9A%A1%EF%B8%8F+Evolving+builds+%F0%9F%8D%83+Shipping+legendaries+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
  
  <br/>
  
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/pikachu-animated.svg" alt="Pikachu" width="48" style="margin: 0 10px;">
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/charmander-animated.svg" alt="Charmander" width="48" style="margin: 0 10px;">
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/lucario-animated.svg" alt="Lucario" width="48" style="margin: 0 10px;">
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/greninja-animated.svg" alt="Greninja" width="48" style="margin: 0 10px;">
</div>

## 🥊 Pokémon Battle Showcase

<div align="center">
  <img src="https://img.shields.io/badge/🥊_BATTLE_SHOWCASE-LUCARIO_vs_CHARIZARD-red?style=for-the-badge&logo=github&logoColor=white" alt="Battle Showcase" />
</div>

<div align="center" style="background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460); border: 4px solid #ffd700; border-radius: 20px; padding: 20px; margin: 20px 0; box-shadow: 0 0 30px rgba(255, 215, 0, 0.5);">
  
  <!-- Battle Field -->
  <div style="position: relative; background: linear-gradient(45deg, #2c5530, #3a6b3f, #4a7c59); border: 3px solid #8b4513; border-radius: 15px; padding: 30px; min-height: 400px; margin: 20px 0;">
    
    <!-- Battle Title -->
    <div style="text-align: center; font-size: 18px; color: #ffd700; margin-bottom: 20px; font-family: monospace; font-weight: bold;">
      🥊 POKÉMON BATTLE - LUCARIO vs CHARIZARD 🥊
    </div>
    
    <!-- Lucario -->
    <div style="position: absolute; bottom: 50px; left: 50px; width: 80px; height: 80px; animation: bounce 2s ease-in-out infinite;">
      <div style="width: 80px; height: 80px; background: #4ECDC4; border: 3px solid #26D0CE; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 40px;">
        🥋
      </div>
      <div style="position: absolute; bottom: -30px; left: 0; background: rgba(0,0,0,0.8); border: 2px solid #ffd700; border-radius: 8px; padding: 5px; color: #fff; font-size: 8px; text-align: center; width: 80px;">
        <div><strong>Lucario</strong></div>
        <div>Level: 50</div>
        <div>HP: <span id="lucarioHP">100/100</span></div>
      </div>
    </div>
    
    <!-- Charizard -->
    <div style="position: absolute; top: 50px; right: 50px; width: 80px; height: 80px; animation: bounce 2s ease-in-out infinite 1s;">
      <div style="width: 80px; height: 80px; background: #FF6B6B; border: 3px solid #FF4757; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 40px;">
        🔥
      </div>
      <div style="position: absolute; top: -30px; right: 0; background: rgba(0,0,0,0.8); border: 2px solid #ffd700; border-radius: 8px; padding: 5px; color: #fff; font-size: 8px; text-align: center; width: 80px;">
        <div><strong>Charizard</strong></div>
        <div>Level: 50</div>
        <div>HP: <span id="charizardHP">85/100</span></div>
      </div>
    </div>
    
    <!-- VS Text -->
    <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); font-size: 36px; font-weight: bold; color: #ffd700; text-shadow: 2px 2px 4px rgba(0,0,0,0.8);">
      VS
    </div>
    
    <!-- Battle Menu -->
    <div id="battleMenu" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0,0,0,0.9); border: 3px solid #ffd700; border-radius: 15px; padding: 20px;">
      <div style="text-align: center; font-size: 12px; color: #ffd700; margin-bottom: 15px; font-family: monospace;">What will Lucario do?</div>
      <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
        <button onclick="showMoves()" style="padding: 15px 20px; background: linear-gradient(45deg, #ff6b6b, #ff8e8e); border: 2px solid #ff4757; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">⚔️ FIGHT</button>
        <button onclick="run()" style="padding: 15px 20px; background: linear-gradient(45deg, #f9ca24, #f0932b); border: 2px solid #f39c12; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">🏃 RUN</button>
      </div>
    </div>
    
    <!-- Moves Menu -->
    <div id="movesMenu" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0,0,0,0.9); border: 3px solid #ffd700; border-radius: 15px; padding: 20px; display: none;">
      <div style="text-align: center; font-size: 12px; color: #ffd700; margin-bottom: 15px; font-family: monospace;">Choose a move!</div>
      <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
        <button onclick="useMove('Aura Sphere')" style="padding: 15px 20px; background: linear-gradient(45deg, #4ecdc4, #7dd3fc); border: 2px solid #26d0ce; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">Aura Sphere</button>
        <button onclick="useMove('Close Combat')" style="padding: 15px 20px; background: linear-gradient(45deg, #4ecdc4, #7dd3fc); border: 2px solid #26d0ce; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">Close Combat</button>
        <button onclick="useMove('Bone Rush')" style="padding: 15px 20px; background: linear-gradient(45deg, #4ecdc4, #7dd3fc); border: 2px solid #26d0ce; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">Bone Rush</button>
        <button onclick="useMove('Metal Claw')" style="padding: 15px 20px; background: linear-gradient(45deg, #4ecdc4, #7dd3fc); border: 2px solid #26d0ce; border-radius: 10px; color: white; font-family: monospace; font-size: 10px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);">Metal Claw</button>
      </div>
    </div>
    
    <!-- Battle Log -->
    <div style="position: absolute; top: 20px; left: 20px; right: 20px; background: rgba(0,0,0,0.8); border: 2px solid #ffd700; border-radius: 10px; padding: 15px; color: #fff; font-size: 10px; max-height: 80px; overflow-y: auto; font-family: monospace;">
      <div id="battleLog">🥊 Battle started! What will Lucario do?</div>
    </div>
    
    <!-- Battle Stats -->
    <div style="position: absolute; top: 20px; right: 20px; background: rgba(0,0,0,0.8); border: 2px solid #ffd700; border-radius: 10px; padding: 15px; color: #fff; font-size: 8px; font-family: monospace;">
      <div style="display: flex; justify-content: space-between; margin: 3px 0;"><span>Turn:</span><span id="turnCount">1</span></div>
      <div style="display: flex; justify-content: space-between; margin: 3px 0;"><span>Lucario Wins:</span><span id="lucarioWins">0</span></div>
      <div style="display: flex; justify-content: space-between; margin: 3px 0;"><span>Charizard Wins:</span><span id="charizardWins">0</span></div>
      <div style="display: flex; justify-content: space-between; margin: 3px 0;"><span>Total Battles:</span><span id="totalBattles">0</span></div>
    </div>
    
  </div>
  
  <div style="text-align: center; color: #ccc; font-size: 12px; margin-top: 10px;">
    🎮 Interactive battle system • Click buttons to play! • Choose your moves and battle!
  </div>
  
</div>

<style>
@keyframes bounce {
  0%, 100% { transform: translateY(0px) scale(1); }
  50% { transform: translateY(-10px) scale(1.1); }
}
</style>

<script>
// Battle state
let battleState = {
  lucarioHP: 100,
  charizardHP: 100,
  lucarioMaxHP: 100,
  charizardMaxHP: 100,
  turn: 1,
  lucarioWins: 0,
  charizardWins: 0,
  totalBattles: 0,
  isBattleActive: true
};

// Move data
const moves = {
  'Aura Sphere': { power: 20, type: 'Fighting', accuracy: 95 },
  'Close Combat': { power: 25, type: 'Fighting', accuracy: 90 },
  'Bone Rush': { power: 15, type: 'Ground', accuracy: 85 },
  'Metal Claw': { power: 18, type: 'Steel', accuracy: 90 }
};

// Show moves menu
function showMoves() {
  document.getElementById('battleMenu').style.display = 'none';
  document.getElementById('movesMenu').style.display = 'block';
}

// Use move
function useMove(moveName) {
  if (!battleState.isBattleActive) return;
  
  const move = moves[moveName];
  const accuracy = Math.random() * 100;
  
  if (accuracy > move.accuracy) {
    addBattleMessage(`❌ ${moveName} missed!`);
    document.getElementById('movesMenu').style.display = 'none';
    setTimeout(() => charizardAttack(), 1000);
    return;
  }
  
  const damage = Math.floor(Math.random() * move.power) + move.power;
  const isCritical = Math.random() < 0.2;
  const finalDamage = isCritical ? damage * 2 : damage;
  
  battleState.charizardHP = Math.max(0, battleState.charizardHP - finalDamage);
  
  if (isCritical) {
    addBattleMessage(`💥 Lucario used ${moveName}! Critical hit! ${finalDamage} damage!`);
  } else {
    addBattleMessage(`⚔️ Lucario used ${moveName}! ${finalDamage} damage!`);
  }
  
  updateDisplay();
  checkBattleEnd();
  
  if (battleState.isBattleActive) {
    document.getElementById('movesMenu').style.display = 'none';
    setTimeout(() => charizardAttack(), 1000);
  }
}

// Run function
function run() {
  if (!battleState.isBattleActive) return;
  
  addBattleMessage(`🏃 Lucario ran away! Battle ended!`);
  battleState.isBattleActive = false;
  resetBattle();
}

// Charizard attack
function charizardAttack() {
  if (!battleState.isBattleActive) return;
  
  const moves = ['Flamethrower', 'Dragon Claw', 'Wing Attack', 'Fire Blast'];
  const move = moves[Math.floor(Math.random() * moves.length)];
  const damage = Math.floor(Math.random() * 25) + 15;
  const isCritical = Math.random() < 0.15;
  const finalDamage = isCritical ? damage * 2 : damage;
  
  battleState.lucarioHP = Math.max(0, battleState.lucarioHP - finalDamage);
  
  if (isCritical) {
    addBattleMessage(`💥 Charizard used ${move}! Critical hit! ${finalDamage} damage!`);
  } else {
    addBattleMessage(`🔥 Charizard used ${move}! ${finalDamage} damage!`);
  }
  
  updateDisplay();
  checkBattleEnd();
  
  if (battleState.isBattleActive) {
    setTimeout(() => showBattleMenu(), 1000);
  }
}

// Update display
function updateDisplay() {
  document.getElementById('lucarioHP').textContent = `${battleState.lucarioHP}/${battleState.lucarioMaxHP}`;
  document.getElementById('charizardHP').textContent = `${battleState.charizardHP}/${battleState.charizardMaxHP}`;
  document.getElementById('turnCount').textContent = battleState.turn;
  document.getElementById('lucarioWins').textContent = battleState.lucarioWins;
  document.getElementById('charizardWins').textContent = battleState.charizardWins;
  document.getElementById('totalBattles').textContent = battleState.totalBattles;
}

// Add battle message
function addBattleMessage(message) {
  const battleLog = document.getElementById('battleLog');
  const messageDiv = document.createElement('div');
  messageDiv.textContent = message;
  battleLog.appendChild(messageDiv);
  battleLog.scrollTop = battleLog.scrollHeight;
}

// Check battle end
function checkBattleEnd() {
  if (battleState.lucarioHP <= 0) {
    battleState.charizardWins++;
    battleState.totalBattles++;
    battleState.isBattleActive = false;
    addBattleMessage("🔥 Charizard wins! 🔥");
  } else if (battleState.charizardHP <= 0) {
    battleState.lucarioWins++;
    battleState.totalBattles++;
    battleState.isBattleActive = false;
    addBattleMessage("🥋 Lucario wins! 🥋");
  } else {
    battleState.turn++;
  }
}

// Show battle menu
function showBattleMenu() {
  document.getElementById('battleMenu').style.display = 'block';
  document.getElementById('movesMenu').style.display = 'none';
}

// Reset battle
function resetBattle() {
  battleState.lucarioHP = 100;
  battleState.charizardHP = 100;
  battleState.turn = 1;
  battleState.isBattleActive = true;
  updateDisplay();
  showBattleMenu();
  addBattleMessage("🥊 New battle started! What will Lucario do?");
}

// Initialize on load
document.addEventListener('DOMContentLoaded', function() {
  resetBattle();
});
</script>

<a id="trainer-card"></a>

### Trainer Card

<div align="center">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/trainer_card.png" alt="Trainer Card" width="400">

</div>

<a id="skills"></a>

### Skills

#### 🧠 Core Programming Languages

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" />
</div>

#### ⚙️ Frameworks & Tools

<div align="center">
  
  <!-- Backend -->
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />

  <br/>

  <!-- Frontend -->
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=111" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" />

  <br/>

  <!-- Databases -->
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />

  <br/>

  <!-- Cloud & Big Data -->
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=111" />
  <img src="https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apache&logoColor=111" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Hive-FFCC00?style=for-the-badge&logo=apache&logoColor=111" />
  <img src="https://img.shields.io/badge/Pig-FFC0CB?style=for-the-badge&logo=apache&logoColor=111" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />

  <br/>

  <!-- Containers & CI/CD -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />

</div>

#### 🤖 AI/ML & Data Science

<div align="center">
  <!-- Libraries -->
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=111" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FCC72B?style=for-the-badge&logo=huggingface&logoColor=111" />
</div>

- Expertise: NLP (Transformers, Hugging Face), Computer Vision, Anomaly Detection, Online Learning
- Projects: Vehicle Detection & Forecasting, Threat Intelligence Automation, PINN‑based Rocket Simulation, Sentiment Analysis Engine

#### 🌐 APIs, Microservices & Integrations

- REST APIs with NestJS / FastAPI
- WebSocket & LiveKit real‑time integration
- Redis caching, Kafka event streaming
- JWT and OAuth authentication

#### 🚀 DevOps & Testing

<div align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" />
  <img src="https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&logo=mocha&logoColor=white" />
</div>

<a id="gym-badges"></a>

### 🏆 Gym Badge Collection

<div align="center">

<a href="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/dynamic-gym-badges.html" target="_blank">
  <img src="https://img.shields.io/badge/🏆_GYM_BADGES-REAL_TRACKING-red?style=for-the-badge&logo=github&logoColor=white" alt="Gym Badges" />
</a>

<br/><br/>

<div style="background: linear-gradient(135deg, #1a1a1a, #2d2d2d); border: 4px solid #ffd700; border-radius: 25px; padding: 20px; max-width: 800px; margin: 0 auto; box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);">

<div style="text-align: center; font-size: 18px; color: #ffd700; margin-bottom: 20px; font-weight: bold; font-family: monospace;">
🏆 GYM BADGE COLLECTION 🏆
</div>

<div style="display: flex; justify-content: center; align-items: center; gap: 15px; margin: 20px 0; flex-wrap: nowrap;">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/fire-badge.svg" alt="Fire Badge" width="60" title="🔥 Fire Badge - Hot Streak (3-day coding streak)">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/water-badge.svg" alt="Water Badge" width="60" title="💧 Water Badge - Deep Diver (5+ repositories)">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/electric-badge.svg" alt="Electric Badge" width="60" title="⚡ Electric Badge - Power User (50+ commits)">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/grass-badge.svg" alt="Grass Badge" width="60" title="🌿 Grass Badge - Code Gardener (3+ languages)">

</div>

<div style="background: #ffd700; color: #1a1a1a; padding: 10px 20px; border-radius: 15px; text-align: center; font-weight: bold; margin: 20px 0; font-family: monospace; font-size: 10px;">
🏆 BADGES EARNED: 3/4 🏆
</div>


</div>

</div>

<a id="quest-log"></a>

### Quest Log

<div align="center">

<a href="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/pokemon-quest-log.html" target="_blank">
  <img src="https://img.shields.io/badge/🎮_QUEST_LOG-POKÉMON_EDITION-red?style=for-the-badge&logo=github&logoColor=white" alt="Quest Log" />
</a>

<br/><br/>

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/lucario-animated.svg" alt="Lucario" width="32" style="float: left; margin-right: 10px;">

<br/><br/>

<div style="background: linear-gradient(135deg, #dc2626, #b91c1c); border: 4px solid #1f2937; border-radius: 25px; padding: 20px; max-width: 600px; margin: 0 auto; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">

<div style="background: linear-gradient(135deg, #1e293b, #0f172a); border: 3px solid #374151; border-radius: 8px; padding: 20px; margin: 10px 0;">

<div style="text-align: center; font-size: 18px; color: #60a5fa; margin-bottom: 20px; font-weight: bold; font-family: monospace;">
🎮 QUEST LOG v3.0 - POKÉMON EDITION 🎮
</div>

<div style="margin: 15px 0; padding: 10px; background: rgba(255,255,255,0.1); border-radius: 5px;">
<div style="color: #fbbf24; font-weight: bold; font-size: 14px; font-family: monospace;">⚔️ QUEST: Advanced System Design</div>
<div style="color: #a78bfa; font-size: 12px; margin: 5px 0; font-family: monospace;">Building distributed systems • Kafka + Redis patterns</div>
<div style="background: #374151; height: 8px; border-radius: 4px; margin: 5px 0; overflow: hidden;">
<div style="height: 100%; width: 75%; background: #3b82f6; border-radius: 4px;"></div>
</div>
<div style="text-align: right; color: white; font-weight: bold; font-family: monospace;">75%</div>
</div>

<div style="margin: 15px 0; padding: 10px; background: rgba(255,255,255,0.1); border-radius: 5px;">
<div style="color: #fbbf24; font-weight: bold; font-size: 14px; font-family: monospace;">🧠 QUEST: Advanced ML & Deep Learning</div>
<div style="color: #a78bfa; font-size: 12px; margin: 5px 0; font-family: monospace;">Transformers, BERT, GPT architectures • Fine-tuning</div>
<div style="background: #374151; height: 8px; border-radius: 4px; margin: 5px 0; overflow: hidden;">
<div style="height: 100%; width: 60%; background: #eab308; border-radius: 4px;"></div>
</div>
<div style="text-align: right; color: white; font-weight: bold; font-family: monospace;">60%</div>
</div>

<div style="margin: 15px 0; padding: 10px; background: rgba(255,255,255,0.1); border-radius: 5px;">
<div style="color: #fbbf24; font-weight: bold; font-size: 14px; font-family: monospace;">☁️ QUEST: Cloud-Native Architecture</div>
<div style="color: #a78bfa; font-size: 12px; margin: 5px 0; font-family: monospace;">Kubernetes + Helm deployments • Microservices patterns</div>
<div style="background: #374151; height: 8px; border-radius: 4px; margin: 5px 0; overflow: hidden;">
<div style="height: 100%; width: 80%; background: #22c55e; border-radius: 4px;"></div>
</div>
<div style="text-align: right; color: white; font-weight: bold; font-family: monospace;">80%</div>
</div>

<div style="background: #fbbf24; color: #1f2937; padding: 10px 20px; border-radius: 15px; text-align: center; font-weight: bold; margin: 20px 0; font-family: monospace;">
🏆 Legendary Quest Badge: 3/12
</div>

</div>


</div>

</div>

<a id="pokedex-projects"></a>

### Pokédex (Projects)

<div align="center">

<img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/pokedex-device.svg" alt="Pokédex Device" width="400" height="600" style="border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">

</div>

#### 📱 **Project Links**
- **#001**: [`Agriculture_MIC`](https://github.com/AsukaFurukawa/Agriculture_MIC) - Intelligent crop insights
- **#002**: [`AI-Driven-Structural-Health`](https://github.com/AsukaFurukawa/AI-Driven-Structural-Health-Monitoring-Using-Simulated-Drone-Imagery) - Vision models for damage detection  
- **#003**: [`BigData-Sentiment-Analysis`](https://github.com/AsukaFurukawa/BigData-Sentiment-Analysis) - Scalable sentiment pipelines
- **#004**: [`OmniOrchestrator`](https://github.com/AsukaFurukawa/OmniOrchestrator) - Automations and workflows
- **#005**: [`MyBlog`](https://github.com/AsukaFurukawa/MyBlog) - Developer blog and notes
- **#006**: [`ResearchHub`](https://github.com/AsukaFurukawa/ResearchHub) - Experiments and notebooks

<p align="center">
  <a href="https://github.com/AsukaFurukawa?tab=repositories">
    <img src="https://img.shields.io/badge/View_All_Repos-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<a id="stats"></a>

### Stats & Activity

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=AsukaFurukawa&show_icons=true&theme=tokyonight&bg_color=000000&title_color=00e6e6&icon_color=ff3e3e&text_color=c9d1d9" />
  <img height="160" src="https://streak-stats.demolab.com?user=AsukaFurukawa&theme=tokyonight&background=000000&ring=00e6e6&fire=ff3e3e&currStreakNum=c9d1d9" />
</div>

<div align="center">
  <img height="140" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AsukaFurukawa&layout=compact&theme=tokyonight&bg_color=000000&title_color=00e6e6&text_color=c9d1d9" />
</div>

## 🗺️ Pokémon Adventure Map

<div align="center">
  <a href="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/pokemon-adventure-map.html" target="_blank">
    <img src="https://img.shields.io/badge/🗺️_ADVENTURE_MAP-EXPLORE_NOW-red?style=for-the-badge&logo=github&logoColor=white" alt="Adventure Map" />
  </a>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/pokemon-adventure-map.svg" alt="Dynamic Pokémon Adventure Map" width="100%" style="border-radius: 15px; box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);"/>
  
  <p style="color: #ccc; font-size: 12px; margin-top: 10px;">
    🕐 Updates daily with real GitHub data • Last updated: <img src="https://img.shields.io/badge/Dynamic-Real--time-brightgreen?style=flat-square&logo=github" alt="Dynamic"/>
  </p>
</div>

<a id="achievements"></a>

### Achievements

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=AsukaFurukawa&theme=tokyonight&no-frame=true&no-bg=true&row=2&column=3&margin-w=15&margin-h=15" />
</div>

### Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/output/github-contribution-grid-snake-dark.svg" />
    <img alt="snake animation" src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<a id="contact"></a>

### Contact

- **Let's co-op**: Open an issue on this repo or DM on GitHub.
- **Press START**: Star a project and say hi!

<div align="center">
  <img src="https://raw.githubusercontent.com/AsukaFurukawa/AsukaFurukawa/main/assets/divider.svg" alt="Pokéball Divider" width="680">
  <br />
  <sub>Made with ❤️ + 16‑bit vibes. Art assets are original and free to use with attribution.</sub>
</div>


