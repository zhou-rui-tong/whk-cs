<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>whk-重生学霸之路</title>
    <style>
        * { box-sizing: border-box; font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif; transition: all 0.2s ease; }
        :root {
            --primary: #1e3c5c; --accent: #e67e22; --danger: #c0392b; --success: #27ae60;
            --bg: #ecf0f5; --card: #ffffff; --text: #2c3e50; --border: #bdc9d5;
            --love: #d6336c; --rich: #f1c40f; --weekend: #95a5a6;
            --level-sss: #4a1d6d; --level-ss: #7b3f9f; --level-s: #9333ea; --level-a: #e11d48;
            --level-b: #ea580c; --level-c: #16a34a; --level-d: #3b82f6; --level-e: #64748b;
        }
        body { background: var(--bg); color: var(--text); margin: 0; display: flex; flex-direction: column; min-height: 100vh; font-size: 14px; }
        button { cursor: pointer; border: none; border-radius: 8px; font-weight: bold; padding: 8px 16px; background: var(--primary); color: white; }
        button:disabled { opacity: 0.5; cursor: not-allowed; }
        .btn-accent { background: var(--accent); }
        .btn-love { background: var(--love); }
        .btn-rich { background: var(--rich); color: #000; }
        .btn-danger { background: var(--danger); }
        .hidden { display: none !important; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        .overlay { position: fixed; inset: 0; background: rgba(10,20,30,0.9); z-index: 9999; display: flex; justify-content: center; align-items: center; backdrop-filter: blur(6px); }
        .modal-box { background: var(--card); border-radius: 24px; padding: 30px; width: 90%; max-width: 800px; box-shadow: 0 20px 40px rgba(0,0,0,0.5); max-height: 80vh; overflow-y: auto; }
        .modal-title { font-size: 2em; color: var(--primary); border-bottom: 3px solid var(--accent); padding-bottom: 10px; margin-top: 0; }
        header { height: 70px; background: var(--card); border-bottom: 4px solid var(--accent); display: flex; align-items: center; justify-content: space-between; padding: 0 25px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
        .stat-group { display: flex; gap: 20px; flex-wrap: wrap; }
        .stat-pill { background: #f0f6fc; padding: 8px 18px; border-radius: 30px; border: 1px solid var(--border); font-weight: bold; display: flex; align-items: center; gap: 6px; }
        .stat-pill b { color: var(--accent); font-size: 1.2em; }
        .app-body { display: grid; grid-template-columns: 280px 1fr 280px; gap: 20px; padding: 20px; flex: 1; overflow: hidden; }
        .stats-panel { background: var(--card); border-radius: 20px; padding: 20px; border: 1px solid var(--border); overflow-y: auto; box-shadow: 0 4px 10px rgba(0,0,0,0.03); }
        .stats-panel h3 { margin-top: 0; color: var(--primary); border-bottom: 2px solid var(--accent); padding-bottom: 8px; }
        .stat-item { display: flex; justify-content: space-between; margin: 12px 0; font-size: 1.1em; }
        .stat-value { font-weight: bold; color: var(--accent); }
        .subject-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 15px; }
        .subject-card { background: #f8fafc; border-radius: 12px; padding: 10px; text-align: center; border: 1px solid #dde3ed; }
        .subject-label { font-size: 0.8em; color: #4f6b8a; }
        .subject-score { font-size: 1.8em; font-weight: 800; color: white; text-shadow: 0 1px 2px rgba(0,0,0,0.3); padding: 4px 0; border-radius: 8px; }
        .subject-exp { font-size: 0.7em; color: #6c7a8d; }
        .loan-info { background: #fef5e7; padding: 10px; border-radius: 12px; margin-top: 15px; border: 1px solid var(--rich); }
        .interest-note { font-size: 0.8em; color: var(--danger); margin-top: 5px; }
        .grade-info { background: #e0f2fe; padding: 8px; border-radius: 8px; margin-top: 10px; text-align: center; font-weight: bold; }
        .action-panel { background: var(--card); border-radius: 20px; padding: 20px; border: 1px solid var(--border); overflow-y: auto; display: flex; flex-direction: column; }
        .day-info { background: var(--primary); color: white; padding: 15px; border-radius: 16px; margin-bottom: 20px; text-align: center; font-size: 1.3em; font-weight: bold; }
        .action-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 20px; }
        .action-card { background: #f8fafc; border: 1px solid var(--border); border-radius: 16px; padding: 16px; cursor: pointer; transition: 0.2s; text-align: center; }
        .action-card.weekend-locked { background: #ecf0f1; color: #7f8c8d; pointer-events: none; opacity: 0.6; }
        .action-card:hover:not(.weekend-locked) { border-color: var(--accent); transform: translateY(-3px); box-shadow: 0 6px 12px rgba(230,126,34,0.15); }
        .action-icon { font-size: 2.5em; margin-bottom: 8px; }
        .action-title { font-weight: bold; font-size: 1.1em; margin-bottom: 4px; }
        .action-cost { font-size: 0.85em; color: #64748b; }
        .sub-panel { background: #f0f6fc; border-radius: 16px; padding: 15px; margin-bottom: 15px; }
        .subject-buttons, .love-buttons { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; margin-top: 10px; }
        .event-log { background: #1e2f3f; color: #eef5fc; border-radius: 16px; padding: 15px; flex: 1; overflow-y: auto; font-size: 0.9em; border-top: 4px solid var(--accent); }
        .log-entry { margin-bottom: 8px; padding-bottom: 6px; border-bottom: 1px dashed #3a5770; }
        .log-eff { color: #f9d77e; font-weight: bold; }
        .social-panel { background: var(--card); border-radius: 20px; padding: 20px; border: 1px solid var(--border); overflow-y: auto; }
        .love-card { border-radius: 16px; padding: 15px; margin-bottom: 15px; border: 2px solid; position: relative; }
        .crush-card { border-color: var(--love); background: #fff0f5; }
        .rich-card { border-color: var(--rich); background: #fef5e7; }
        .normal-card { border-color: var(--border); background: #f8fafc; }
        .love-name { font-size: 1.3em; font-weight: bold; }
        .dating-tag { position: absolute; top: 10px; right: 10px; background: var(--love); color: white; padding: 2px 8px; border-radius: 20px; font-size: 0.7em; }
        .love-feel { margin: 8px 0; }
        .heart-bar { height: 10px; background: #ffccd5; border-radius: 10px; overflow: hidden; margin: 5px 0; }
        .heart-fill { height: 100%; background: #ff4d6d; width: 0%; }
        .no-contact { color: #7f8c8d; font-style: italic; }
        .button-group { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px; }
        .button-group button { flex: 1; min-width: 80px; }
        .name-input-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 15px 0; }
        .name-input-item { display: flex; flex-direction: column; }
        .name-input-item label { font-weight: bold; margin-bottom: 4px; }
        .name-input-item input { padding: 8px; border: 1px solid var(--border); border-radius: 6px; }
        #start-overlay .story-content { background: #fef7e8; padding: 20px; border-radius: 16px; border-left: 6px solid var(--accent); line-height: 1.8; margin: 20px 0; }
        .gender-select { display: flex; gap: 20px; justify-content: center; margin: 15px 0; }
        .gender-select label { display: flex; align-items: center; gap: 5px; cursor: pointer; }
        .stock-table { width: 100%; border-collapse: collapse; margin-top: 10px; font-size: 0.9em; }
        .stock-table th, .stock-table td { padding: 8px 6px; text-align: center; border: 1px solid var(--border); vertical-align: middle; }
        .stock-table th { background: var(--primary); color: white; }
        .stock-input { width: 60px; padding: 4px; text-align: center; }
        .stock-table button { margin: 2px; padding: 4px 8px; font-size: 0.8rem; }
        .exam-table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        .exam-table th, .exam-table td { padding: 8px; text-align: center; border: 1px solid var(--border); }
        .exam-table th { background: var(--primary); color: white; }
        .exam-cell { transform: scale(0); opacity: 0; font-weight: bold; }
        .exam-cell.pop { animation: popIn 0.3s forwards; }
        @keyframes popIn { to { transform: scale(1); opacity: 1; } }
    </style>
</head>
<body>

<div id="start-overlay" class="overlay">
    <div class="modal-box">
        <h1 class="modal-title">💔 whk-重生学霸之路</h1>
        <div class="story-content" id="story-text">
            <p>前世，你是OI赛场上的希望之星，却为了追求心上人，放弃了集训队选拔……最后对方保送985，而你OI失利、文化课一落千丈，只考上一所专科。</p>
            <p>毕业五年后的同学会上，看到对方挽着优秀伴侣的手，你后悔莫及。当晚酗酒过度，心梗猝死。</p>
            <p><strong>上天给了你一次重来的机会。</strong>你回到了高考前，这次你要逆天改命！</p>
        </div>
        <div class="gender-select">
            <label><input type="radio" name="gender" value="male" checked> 🧑 男生</label>
            <label><input type="radio" name="gender" value="female"> 👩 女生</label>
        </div>
        <div style="margin: 20px 0;">
            <label>你回到了高考前 <input type="number" id="start-days" min="1" max="1000" value="200" style="width:80px;"> 天</label>
        </div>
        <h3 id="char-name-title">为恋爱角色命名</h3>
        <div id="name-input-grid" class="name-input-grid">
            <div class="name-input-item">
                <label id="label-crush">🌸 校花</label>
                <input type="text" id="name-crush" placeholder="柳如烟" value="柳如烟">
            </div>
            <div class="name-input-item">
                <label id="label-rich">💎 千金</label>
                <input type="text" id="name-rich" placeholder="林薇薇" value="林薇薇">
            </div>
            <div class="name-input-item">
                <label id="label-normal1">普通女生</label>
                <input type="text" id="name-normal1" placeholder="陈雨桐" value="陈雨桐">
            </div>
            <div class="name-input-item">
                <label id="label-normal2">普通女生</label>
                <input type="text" id="name-normal2" placeholder="赵灵儿" value="赵灵儿">
            </div>
        </div>
        <div style="display: flex; gap: 15px; justify-content: center; margin: 20px 0;">
            <button class="btn-accent" onclick="startGame('easy')">🚀 简单模式</button>
            <button onclick="startGame('hard')">🔥 困难模式</button>
        </div>
    </div>
</div>

<header id="main-header" class="hidden">
    <div style="font-size:1.5rem; font-weight:900; color:var(--primary);">📚 高考冲刺 · 重生之路</div>
    <div class="stat-group">
        <div class="stat-pill">⏰ 高考倒计时: <b id="ui-days-left">200</b>天</div>
        <div class="stat-pill">📆 <span id="ui-weekday">周一</span></div>
        <div class="stat-pill">💰 零花钱: <b id="ui-money">0</b></div>
        <div class="stat-pill">🧠 决心: <b id="ui-determination">50</b>/100</div>
        <div class="stat-pill">😰 压力: <b id="ui-stress">20</b>/100</div>
    </div>
</header>

<div class="app-body hidden" id="main-body">
    <div class="stats-panel">
        <h3>📊 我的状态</h3>
        <div class="stat-item"><span>✨ 魅力</span><span class="stat-value" id="stat-charm">60</span>/100</div>
        <div class="stat-item"><span>💪 决心</span><span class="stat-value" id="stat-determination">50</span>/100</div>
        <div class="stat-item"><span>😰 压力</span><span class="stat-value" id="stat-stress">20</span>/100</div>
        <div class="stat-item"><span>💰 零花钱</span><span class="stat-value" id="stat-money">0</span></div>
        <div class="loan-info">
            <div class="stat-item"><span>🏦 银行贷款</span><span class="stat-value" id="stat-bank-loan">0</span>元</div>
            <div class="stat-item"><span>⚠️ 高利贷</span><span class="stat-value" id="stat-usury-loan">0</span>元</div>
            <div class="interest-note">银行贷款日息1%，每30天强制还清；高利贷日息<span id="usury-rate">7</span>%</div>
            <button class="btn-rich" onclick="showLoanPanel()" style="width:100%; margin-top:5px;">💰 贷款管理</button>
        </div>
        <div class="grade-info" id="grade-display">当前年级: 高三冲刺</div>
        <h3 style="margin-top: 25px;">📚 学科等级</h3>
        <div class="subject-grid" id="subject-scores"></div>
        <div style="margin-top: 20px; background:#f0f6fc; padding:10px; border-radius:12px;">
            <p><strong>🏫 教室环境</strong> Lv.<span id="fac-level">0</span> (学习效率+<span id="fac-bonus">0</span>%)</p>
        </div>
        <h3 style="margin-top: 25px;">📈 炒股能力</h3>
        <div class="subject-card" style="margin-bottom:10px;"><div class="subject-label">炒股等级</div><div class="subject-score" id="stock-level" style="background:var(--level-e);">E</div><div class="subject-exp" id="stock-exp">0/20</div></div>
    </div>

    <div class="action-panel">
        <div class="day-info" id="day-info">
            距离高考 <span id="current-days">200</span> 天 · <span id="current-weekday">周一</span>
        </div>
        <div class="action-grid" id="action-buttons"></div>
        <!-- 子面板 -->
        <div id="train-panel" class="sub-panel hidden"><h4>选择特训科目 (价格随等级提升)</h4><div class="subject-buttons" id="train-subjects"></div><button onclick="hidePanels()">取消</button></div>
        <div id="date-panel" class="sub-panel hidden"><h4>和谁约会？(花费随机20~80💰)</h4><div class="love-buttons" id="date-love"></div><button onclick="hidePanels()">取消</button></div>
        <div id="work-panel" class="sub-panel hidden"><h4>选择打工方式</h4><div class="subject-buttons" id="work-options"><button onclick="doWork('easy')">发传单</button><button onclick="doWork('hard')">工地搬砖</button><button onclick="doWork('tutor')">家教</button></div><button onclick="hidePanels()">取消</button></div>
        <div id="loan-panel" class="sub-panel hidden"><h4>💸 贷款管理</h4>
            <p>🏦 银行贷款: <span id="panel-bank-loan">0</span>元 (上限: <span id="bank-limit">10000</span>元, 日息1%, 每30天强制还清)</p>
            <p>⚠️ 高利贷: <span id="panel-usury-loan">0</span>元 (日息<span id="usury-rate-panel">7</span>%, 高考后必须还清)</p>
            <div><button onclick="takeBankLoan(1000)">借银行贷款1000</button><button onclick="takeBankLoan(5000)">借5000</button><button onclick="takeBankLoan(10000)">借10000</button></div>
            <div><button onclick="takeUsuryLoan(1000)">借高利贷1000</button><button onclick="takeUsuryLoan(5000)">借5000</button><button onclick="takeUsuryLoan(10000)">借10000</button></div>
            <div style="margin-top:10px;">
                <label>银行贷款还款金额: <input type="number" id="bank-repay-amount" placeholder="金额" style="width:100px;"></label>
                <button onclick="repayBankLoanPartial()">部分还款</button>
                <button onclick="repayAllBankLoan()">一键还清</button>
            </div>
            <div style="margin-top:10px;">
                <label>高利贷还款金额: <input type="number" id="usury-repay-amount" placeholder="金额" style="width:100px;"></label>
                <button onclick="repayUsuryLoanPartial()">部分还款</button>
                <button onclick="repayAllUsuryLoan()">一键还清</button>
            </div>
            <button onclick="hidePanels()">关闭</button>
        </div>
        <div id="teacher-panel" class="sub-panel hidden" style="border:2px solid var(--danger);"><h4>👨‍🏫 班主任提问</h4><p id="teacher-question"></p><div><button onclick="handleTeacher('try')">尝试回答</button><button onclick="handleTeacher('punish')">站着罚站</button></div></div>
        <div id="loveletter-panel" class="sub-panel hidden" style="border:2px solid var(--love);"><h4>💌 发现情书</h4><p id="loveletter-desc"></p><div><button onclick="handleLoveLetter('find')">花钱寻找</button><button onclick="handleLoveLetter('throw')">扔掉</button></div></div>
        <div id="phone-panel" class="sub-panel hidden" style="border:2px solid var(--danger);"><h4>📱 手机被没收</h4><p id="phone-desc"></p><button onclick="closePhonePanel()">接受现实</button></div>
        <div id="sports-event-panel" class="sub-panel hidden" style="border:2px solid var(--success);"><h4>⛹️ 体育课时间</h4><p id="sports-desc"></p><div><button onclick="handleSports('review')">复习文化课</button><button onclick="handleSports('safe')">稳妥打球</button><button onclick="handleSports('showoff')">秀操作</button></div></div>
        <div id="confession-panel" class="sub-panel hidden" style="border:2px solid var(--love);"><h4>💕 有人向你表白</h4><p id="confession-desc"></p><div><button onclick="handleConfession('accept')">接受</button><button onclick="handleConfession('reject')">拒绝</button></div></div>
        <div id="parent-panel" class="sub-panel hidden" style="border:2px solid var(--primary);"><h4>👨‍👩‍👧 父母来电</h4><p id="parent-desc"></p><div><button onclick="closeParentPanel()">知道了</button></div></div>
        <div id="caught-panel" class="sub-panel hidden" style="border:2px solid var(--danger);"><h4>💔 脚踏两条船被发现了</h4><p id="caught-desc"></p><button onclick="closeCaughtPanel()">面对现实</button></div>
        <div id="suicide-panel" class="sub-panel hidden" style="border:2px solid black; background:#2c3e50; color:white;"><h4>😱 悲剧发生</h4><p id="suicide-desc"></p><button onclick="closeSuicidePanel()">……</button></div>
        <div id="stock-panel" class="sub-panel hidden"><h4>📈 股票交易</h4><div id="stock-list"></div><button onclick="hidePanels()">关闭</button></div>
        <div id="sick-gaokao-panel" class="sub-panel hidden" style="border:2px solid var(--danger); background:#fff0f0;"><h4>🏥 高考前病倒</h4><p id="sick-gaokao-desc"></p><div style="display:flex; gap:10px; justify-content:center;"><button onclick="handleSickGaokao('retry')" class="btn-accent">复读</button><button onclick="handleSickGaokao('quit')" class="btn-danger">步入社会</button></div></div>
        <div class="event-log" id="log-area"><div class="log-entry">✨ 重生回到高考前，这一次要逆天改命！</div></div>
    </div>

    <div class="social-panel" id="social-panel"></div>
</div>

<div id="exam-modal" class="overlay hidden">
    <div class="modal-box" style="max-width:800px; width:95%;">
        <h2 class="modal-title" id="exam-title">月考</h2>
        <p id="exam-rewards" style="text-align:center; color:var(--accent);"></p>
        <div style="overflow-x:auto;">
            <table class="exam-table" id="exam-table">
                <thead id="exam-thead"></thead>
                <tbody id="exam-tbody"></tbody>
            表
        </div>
        <div style="text-align:center; margin-top:20px;">
            <button id="exam-close-btn" class="hidden" onclick="closeExam()">确认成绩</button>
        </div>
    </div>
</div>

<div id="gaokao-modal" class="overlay hidden"><div class="modal-box"><h1 class="modal-title">🎓 高考结束</h1><div id="gaokao-content"></div><div id="marriage-content"></div><button onclick="restartGame()">再玩一次</button></div></div>
<div id="marriage-choice-modal" class="overlay hidden"><div class="modal-box"><h2 class="modal-title">💍 选择共度一生的人</h2><div id="marriage-options"></div><button onclick="selectMarriage('none')">独自生活</button></div></div>
<div id="event-modal" class="overlay hidden"><div class="modal-box"><h2 id="event-title"></h2><p id="event-desc"></p><button onclick="closeEventModal()">确定</button></div></div>

<script>
// ========== 配置 ==========
const SUBJECTS = [
    { id: 'chi', name: '语文', max: 150, exp: 0, level: 'E', threshold: [0,20,50,100,180,260,300,330] },
    { id: 'mat', name: '数学', max: 150, exp: 0, level: 'E' },
    { id: 'eng', name: '英语', max: 150, exp: 0, level: 'E' },
    { id: 'phy', name: '物理', max: 100, exp: 0, level: 'E' },
    { id: 'che', name: '化学', max: 100, exp: 0, level: 'E' },
    { id: 'bio', name: '生物', max: 100, exp: 0, level: 'E' }
];
const LEVELS = ['E','D','C','B','A','S','SS','SSS'];
const LEVEL_THRESHOLD = [0,20,50,100,180,260,300,330];
const TRAIN_PRICE = { 'E':50, 'D':80, 'C':120, 'B':180, 'A':250, 'S':350, 'SS':500, 'SSS':700 };
let stockExp = 0;
let stockLevel = 'E';
function getStockLevel(exp) { for(let i=LEVELS.length-1;i>=0;i--) if(exp>=LEVEL_THRESHOLD[i]) return LEVELS[i]; return 'E'; }
function addStockExp(amt) { stockExp = Math.min(330, stockExp + amt); stockLevel = getStockLevel(stockExp); document.getElementById('stock-level').innerText = stockLevel; document.getElementById('stock-level').style.background = `var(--level-${stockLevel.toLowerCase()})`; document.getElementById('stock-exp').innerText = `${stockExp}/${LEVEL_THRESHOLD[LEVELS.indexOf(stockLevel)+1]||'MAX'}`; }

// 炒股等级对应的上涨概率和幅度修正
const STOCK_UP_PROB = { 'E':0.05, 'D':0.10, 'C':0.20, 'B':0.28, 'A':0.40, 'S':0.45, 'SS':0.52, 'SSS':0.60 };
const STOCK_GAIN_MULTIPLIER = { 'E':0.5, 'D':0.6, 'C':0.7, 'B':0.8, 'A':0.9, 'S':1.0, 'SS':1.2, 'SSS':1.5 };
const STOCK_LOSS_MULTIPLIER = { 'E':1.5, 'D':1.4, 'C':1.3, 'B':1.2, 'A':1.1, 'S':1.0, 'SS':0.9, 'SSS':0.8 };

// 股票数据（包含委买量/委卖量）
let stocks = [
    { name: '中华联通', price: 80 + Math.floor(Math.random() * 41), bidVol: 500, askVol: 500, prevPrice: 0 },
    { name: '中华移动', price: 80 + Math.floor(Math.random() * 41), bidVol: 500, askVol: 500, prevPrice: 0 },
    { name: '中华电信', price: 80 + Math.floor(Math.random() * 41), bidVol: 500, askVol: 500, prevPrice: 0 }
];
let businessWars = []; // 商战 {stockIdx1, stockIdx2, duration}

let State = {
    daysLeft: 200, weekday: 0, money: 0, determination: 50, stress: 20, charm: 60,
    bankLoan: 0, usuryLoan: 0, facility: 0,
    subjects: JSON.parse(JSON.stringify(SUBJECTS)), loves: [], isGraduated: false, difficulty: 'hard',
    teacherEventToday: false, examCountdown: 30, gender: 'male', loveLetterAttempts: 0,
    stocks: JSON.parse(JSON.stringify(stocks))
};

// 辅助函数
function getSubjectLevel(exp) { for(let i=LEVELS.length-1;i>=0;i--) if(exp>=LEVEL_THRESHOLD[i]) return LEVELS[i]; return 'E'; }
function getLevelIndex(l) { return LEVELS.indexOf(l); }
function getLevelColor(l) { return `var(--level-${l.toLowerCase()})`; }
function getScoreFromExp(exp, max) {
    let level = getSubjectLevel(exp);
    let base = 0;
    switch(level) {
        case 'E': base = 0 + (exp / 20) * 30; break;
        case 'D': base = 30 + ((exp - 20) / 30) * 30; break;
        case 'C': base = 60 + ((exp - 50) / 50) * 30; break;
        case 'B': base = 90 + ((exp - 100) / 80) * 30; break;
        case 'A': base = 120 + ((exp - 180) / 80) * 30; break;
        case 'S': base = 150 + ((exp - 260) / 40) * 30; break;
        case 'SS': base = 180 + ((exp - 300) / 30) * 30; break;
        case 'SSS': base = 210; break;
        default: base = 0;
    }
    return Math.min(max, Math.floor(base));
}
function addSubjectExp(id, amt) {
    let s=State.subjects.find(x=>x.id===id); if(!s) return;
    let isMale = State.gender === 'male';
    let modifier = 1;
    if (isMale) {
        if (id === 'chi' || id === 'eng') modifier = 0.9;
        else if (id === 'mat' || id === 'phy' || id === 'che' || id === 'bio') modifier = 1.1;
    } else {
        if (id === 'chi' || id === 'eng') modifier = 1.1;
        else if (id === 'mat' || id === 'phy' || id === 'che' || id === 'bio') modifier = 0.9;
    }
    let finalAmt = Math.floor(amt * modifier);
    if (finalAmt < 0) finalAmt = 0;
    s.exp = Math.min(330, s.exp + finalAmt);
    let nl=getSubjectLevel(s.exp);
    if(nl!==s.level){ s.level=nl; log(`🎉 ${s.name} 升到 ${nl} 级！`); }
}
function getLove(id) { return State.loves.find(l=>l.id===id); }
function addTrueFeel(loveId, deltaBase) { let l=getLove(loveId); if(!l) return; let delta = deltaBase + Math.floor(Math.random()*21)-10; delta = Math.floor(delta*(0.8+Math.random()*0.7)); delta = Math.max(-20,Math.min(25,delta)); l.trueFeel = Math.min(100,Math.max(0,l.trueFeel+delta)); updateDisplayFeel(l); return delta; }
function updateDisplayFeel(l) { let offset=Math.floor(Math.random()*21)-10; l.feel=Math.min(100,Math.max(0,l.trueFeel+offset)); }
function log(msg,eff='') { let area=document.getElementById('log-area'); area.innerHTML=`<div class="log-entry"><span style="color:#b0d0ff;">[倒计时 ${State.daysLeft}天 ${getWeekdayName(State.weekday)}]</span> ${msg} ${eff?`<span class="log-eff">${eff}</span>`:''}</div>`+area.innerHTML; }
function getWeekdayName(w) { return ['周一','周二','周三','周四','周五','周六','周日'][w]; }
function isWeekend() { return State.weekday===5||State.weekday===6; }
function getAvgLevel() { let t=0; State.subjects.forEach(s=>t+=getLevelIndex(s.level)); return t/6; }
function updateGrade() { let days=State.daysLeft; let grade=days>365?'高二':'高三冲刺'; document.getElementById('grade-display').innerHTML=`当前年级: ${grade}`; }

// 股票更新函数
function updateStocks() {
    for (let i = 0; i < stocks.length; i++) stocks[i].prevPrice = stocks[i].price;
    for (let i = 0; i < stocks.length; i++) {
        let stock = stocks[i];
        let inWar = businessWars.some(w => w.stockIdx1 === i || w.stockIdx2 === i);
        if (Math.random() < 0.02) {
            let isGood = Math.random() < 0.5;
            let baseAmplitude = 0.2 + Math.random() * 0.6;
            let changePercent = isGood ? baseAmplitude * STOCK_GAIN_MULTIPLIER[stockLevel] : -baseAmplitude * STOCK_LOSS_MULTIPLIER[stockLevel];
            let eventDesc = isGood ? `🎉 ${stock.name} 发布重大利好！股价飙升 ${(changePercent*100).toFixed(1)}%` : `💥 ${stock.name} 爆出重大利空！股价暴跌 ${(-changePercent*100).toFixed(1)}%`;
            let newPrice = stock.price * (1 + changePercent);
            newPrice = Math.max(0.01, newPrice);
            stock.price = newPrice;
            log(eventDesc);
            continue;
        }
        if (inWar) {
            let war = businessWars.find(w => w.stockIdx1 === i || w.stockIdx2 === i);
            let otherIdx = (war.stockIdx1 === i) ? war.stockIdx2 : war.stockIdx1;
            let otherStock = stocks[otherIdx];
            let bothDown = Math.random() < 0.3;
            let myChange = 0, otherChange = 0;
            if (bothDown) {
                myChange = -(0.05 + Math.random() * 0.15);
                otherChange = -(0.05 + Math.random() * 0.15);
            } else {
                let myDir = Math.random() < 0.5 ? 1 : -1;
                myChange = myDir * (0.05 + Math.random() * 0.15);
                otherChange = -myChange;
            }
            let newMyPrice = stock.price * (1 + myChange);
            let newOtherPrice = otherStock.price * (1 + otherChange);
            newMyPrice = Math.max(0.01, newMyPrice);
            newOtherPrice = Math.max(0.01, newOtherPrice);
            stock.price = newMyPrice;
            otherStock.price = newOtherPrice;
            log(`⚔️ 商战持续：${stock.name} ${myChange>0?'涨':'跌'} ${Math.abs(myChange*100).toFixed(1)}%，${otherStock.name} ${otherChange>0?'涨':'跌'} ${Math.abs(otherChange*100).toFixed(1)}%`);
            continue;
        }
        let upProb = STOCK_UP_PROB[stockLevel];
        let isUp = Math.random() < upProb;
        let amplitude = 0.03 + Math.random() * 0.07;
        if (isUp) amplitude *= STOCK_GAIN_MULTIPLIER[stockLevel];
        else amplitude *= STOCK_LOSS_MULTIPLIER[stockLevel];
        let changePercent = isUp ? amplitude : -amplitude;
        let newPrice = stock.price * (1 + changePercent);
        newPrice = Math.max(0.01, newPrice);
        stock.price = newPrice;
    }
    for (let i = 0; i < stocks.length; i++) {
        let stock = stocks[i];
        let priceChange = (stock.price - stock.prevPrice) / stock.prevPrice;
        let levelMultiplier = 0.5 + (LEVELS.indexOf(stockLevel) / 16);
        let baseVol = 200 + Math.floor(Math.random() * 400);
        let trendFactor = Math.min(0.5, Math.abs(priceChange) * 10);
        if (priceChange > 0) {
            stock.bidVol = Math.max(10, Math.floor(baseVol * levelMultiplier * (1 + trendFactor)));
            stock.askVol = Math.max(10, Math.floor(baseVol * levelMultiplier * (1 - trendFactor)));
        } else if (priceChange < 0) {
            stock.bidVol = Math.max(10, Math.floor(baseVol * levelMultiplier * (1 - trendFactor)));
            stock.askVol = Math.max(10, Math.floor(baseVol * levelMultiplier * (1 + trendFactor)));
        } else {
            stock.bidVol = Math.max(10, Math.floor(baseVol * levelMultiplier));
            stock.askVol = Math.max(10, Math.floor(baseVol * levelMultiplier));
        }
    }
    for (let i = businessWars.length-1; i >= 0; i--) {
        businessWars[i].duration--;
        if (businessWars[i].duration <= 0) {
            let war = businessWars[i];
            log(`⚔️ 商战结束：${stocks[war.stockIdx1].name} 与 ${stocks[war.stockIdx2].name} 休战。`);
            businessWars.splice(i,1);
        }
    }
    if (stocks.length >= 2 && Math.random() < 0.02) {
        let idx1 = Math.floor(Math.random() * stocks.length);
        let idx2 = Math.floor(Math.random() * stocks.length);
        if (idx1 !== idx2 && !businessWars.some(w => (w.stockIdx1===idx1 && w.stockIdx2===idx2) || (w.stockIdx1===idx2 && w.stockIdx2===idx1))) {
            let duration = 3 + Math.floor(Math.random() * 5);
            businessWars.push({ stockIdx1: idx1, stockIdx2: idx2, duration: duration });
            log(`⚔️ 商战爆发！${stocks[idx1].name} 与 ${stocks[idx2].name} 开战，预计持续 ${duration} 天。`);
        }
    }
    if (stocks.length > 1 && Math.random() < 0.01) {
        let idx = Math.floor(Math.random() * stocks.length);
        let deadStock = stocks[idx];
        if (State[`stock_${idx}`] > 0) {
            State[`stock_${idx}`] = 0;
            log(`💀 ${deadStock.name} 公司倒闭！你持有的股份化为乌有。`);
        } else {
            log(`💀 ${deadStock.name} 公司倒闭！股价归零并从股市摘牌。`);
        }
        stocks.splice(idx,1);
        for (let w of businessWars) {
            if (w.stockIdx1 === idx) w.stockIdx1 = -1;
            if (w.stockIdx2 === idx) w.stockIdx2 = -1;
        }
        businessWars = businessWars.filter(w => w.stockIdx1 !== -1 && w.stockIdx2 !== -1);
    }
}

// 股票界面 (增加一键买入全部)
function showStockPanel() {
    hidePanels();
    let html = '<table class="stock-table"><thead><tr><th>股票</th><th>现价</th><th>委买量</th><th>委卖量</th><th>持有</th><th>买入</th><th>卖出</th><th>快捷操作</th></tr></thead><tbody>';
    for (let i = 0; i < stocks.length; i++) {
        let stock = stocks[i];
        let hold = State[`stock_${i}`] || 0;
        html += `<tr>
                    <td>${stock.name}</td>
                    <td>${stock.price.toFixed(2)}</td>
                    <td>${stock.bidVol}</td>
                    <td>${stock.askVol}</td>
                    <td>${hold}</td>
                    <td><input type="number" id="buy_${i}" class="stock-input" min="1" value="1"> <button onclick="buyStock(${i})">买入</button></td>
                    <td><input type="number" id="sell_${i}" class="stock-input" min="1" value="1"> <button onclick="sellStock(${i})">卖出</button></td>
                    <td><button onclick="buyAllStock(${i})" class="btn-accent">一键买入全部</button> <button onclick="sellAllOneStock(${i})" class="btn-danger">一键卖出全部</button></td>
                 </tr>`;
    }
    html += '</tbody></table><button onclick="hidePanels()">关闭</button>';
    document.getElementById('stock-list').innerHTML = html;
    document.getElementById('stock-panel').classList.remove('hidden');
}
// 买入指定数量
function buyStock(idx) {
    let amount = parseInt(document.getElementById(`buy_${idx}`).value);
    if (isNaN(amount) || amount <= 0) return;
    let stock = stocks[idx];
    if (amount > stock.askVol) { alert(`委卖量不足，当前可买 ${stock.askVol} 股`); return; }
    let cost = stock.price * amount;
    ensureMoney(cost);
    State[`stock_${idx}`] = (State[`stock_${idx}`] || 0) + amount;
    stock.askVol -= amount;
    log(`买入 ${stock.name} ${amount}股，花费 ${cost.toFixed(2)}💰`);
    hidePanels();
    updateUI();
}
// 卖出指定数量
function sellStock(idx) {
    let amount = parseInt(document.getElementById(`sell_${idx}`).value);
    if (isNaN(amount) || amount <= 0) return;
    let stock = stocks[idx];
    let hold = State[`stock_${idx}`] || 0;
    if (amount > hold) { alert(`持有数量不足，当前持有 ${hold} 股`); return; }
    if (amount > stock.bidVol) { alert(`委买量不足，当前可卖 ${stock.bidVol} 股`); return; }
    let income = stock.price * amount;
    State.money += income;
    State[`stock_${idx}`] = hold - amount;
    stock.bidVol -= amount;
    log(`卖出 ${stock.name} ${amount}股，收入 ${income.toFixed(2)}💰`);
    hidePanels();
    updateUI();
}
// 一键买入全部（买光委卖量）
function buyAllStock(idx) {
    let stock = stocks[idx];
    if (stock.askVol === 0) { alert(`委卖量为0，无法买入`); return; }
    let amount = stock.askVol;
    let cost = stock.price * amount;
    ensureMoney(cost);
    State[`stock_${idx}`] = (State[`stock_${idx}`] || 0) + amount;
    stock.askVol = 0;
    log(`一键买入 ${stock.name} ${amount}股，花费 ${cost.toFixed(2)}💰`);
    hidePanels();
    updateUI();
}
// 一键卖出全部（卖光持有，但受委买量限制）
function sellAllOneStock(idx) {
    let stock = stocks[idx];
    let hold = State[`stock_${idx}`] || 0;
    if (hold === 0) { alert(`没有持有 ${stock.name}`); return; }
    let canSell = Math.min(hold, stock.bidVol);
    if (canSell === 0) { alert(`委买量为0，无法卖出`); return; }
    let income = stock.price * canSell;
    State.money += income;
    State[`stock_${idx}`] = hold - canSell;
    stock.bidVol -= canSell;
    log(`一键卖出 ${stock.name} ${canSell}股，收入 ${income.toFixed(2)}💰`);
    if (hold - canSell > 0) log(`剩余 ${hold - canSell}股因委买量不足未能卖出`);
    hidePanels();
    updateUI();
}
function sellAllStocks() {
    let totalIncome = 0;
    for (let i = 0; i < stocks.length; i++) {
        let stock = stocks[i];
        let hold = State[`stock_${i}`] || 0;
        if (hold > 0) {
            let canSell = Math.min(hold, stock.bidVol);
            if (canSell > 0) {
                let income = stock.price * canSell;
                totalIncome += income;
                State.money += income;
                State[`stock_${i}`] = hold - canSell;
                stock.bidVol -= canSell;
                log(`卖出 ${stock.name} ${canSell}股，收入 ${income.toFixed(2)}💰`);
                if (hold - canSell > 0) log(`剩余 ${hold - canSell}股因委买量不足未能卖出`);
            } else {
                log(`未能卖出 ${stock.name}，委买量为0`);
            }
        }
    }
    if (totalIncome > 0) log(`一键卖出完成，总收入 ${totalIncome.toFixed(2)} 元`);
    else alert('没有可卖出的股票或委买量不足');
    hidePanels();
    updateUI();
}

// 贷款系统
function takeBankLoan(amt) {
    let limit = State.difficulty === 'easy' ? 10000 : 6000;
    if (State.bankLoan + amt > limit) { alert(`银行贷款上限 ${limit} 元`); return; }
    State.money += amt;
    State.bankLoan += amt;
    log(`银行贷款 ${amt} 元`, `资金+${amt}`);
    hidePanels(); updateUI();
}
function takeUsuryLoan(amt) {
    State.money += amt;
    State.usuryLoan += amt;
    log(`高利贷 ${amt} 元`, `资金+${amt}`);
    hidePanels(); updateUI();
}
function repayAllBankLoan() {
    if (State.bankLoan === 0) return alert('没有银行贷款');
    if (State.money < State.bankLoan) {
        let need = State.bankLoan - State.money;
        State.usuryLoan += need;
        State.money = 0;
        log(`零花钱不足，自动借高利贷 ${need} 元偿还银行贷款`, `高利贷+${need}`);
    } else {
        State.money -= State.bankLoan;
    }
    State.bankLoan = 0;
    log(`还清银行贷款`);
    hidePanels(); updateUI();
}
function repayAllUsuryLoan() {
    if (State.usuryLoan === 0) return alert('没有高利贷');
    if (State.money < State.usuryLoan) { alert('零花钱不足，无法还清高利贷！'); return; }
    State.money -= State.usuryLoan;
    State.usuryLoan = 0;
    log(`还清高利贷`);
    hidePanels(); updateUI();
}
function repayBankLoanPartial() {
    let amount = parseInt(document.getElementById('bank-repay-amount').value);
    if (isNaN(amount) || amount <= 0) { alert('请输入有效金额'); return; }
    if (amount > State.bankLoan) { alert('还款金额超过贷款总额'); return; }
    if (State.money < amount) { alert('零花钱不足'); return; }
    State.money -= amount;
    State.bankLoan -= amount;
    log(`偿还银行贷款 ${amount} 元`, `银行贷款剩余 ${State.bankLoan}`);
    hidePanels(); updateUI();
}
function repayUsuryLoanPartial() {
    let amount = parseInt(document.getElementById('usury-repay-amount').value);
    if (isNaN(amount) || amount <= 0) { alert('请输入有效金额'); return; }
    if (amount > State.usuryLoan) { alert('还款金额超过高利贷总额'); return; }
    if (State.money < amount) { alert('零花钱不足'); return; }
    State.money -= amount;
    State.usuryLoan -= amount;
    log(`偿还高利贷 ${amount} 元`, `高利贷剩余 ${State.usuryLoan}`);
    hidePanels(); updateUI();
}
function ensureMoney(amount) {
    if (State.money >= amount) { State.money -= amount; return true; }
    let need = amount - State.money;
    State.money = 0;
    State.usuryLoan += need;
    log(`⚠️ 零花钱不足，自动借高利贷 ${need} 元支付`, `高利贷+${need}`);
    return true;
}

// 提升形象
function improveImage() {
    let cost = State.difficulty === 'easy' ? 100 + Math.floor(Math.random() * 101) : 150 + Math.floor(Math.random() * 101);
    ensureMoney(cost);
    let anyImprove = false;
    for (let love of State.loves) {
        let gain = State.difficulty === 'easy' ? Math.floor(Math.random() * 10) : Math.floor(Math.random() * 5);
        if (gain > 0) {
            addTrueFeel(love.id, gain);
            anyImprove = true;
        }
    }
    const msgs = [`你精心打理了发型，整个人精神多了！`,`你换了一身新衣服，气质提升！`,`你开始注重仪表，看起来更有魅力了。`,`你认真护肤，皮肤状态好了很多。`,`你修剪了胡须/整理了眉毛，清爽了不少。`,`你练习了仪态，走起路来更有自信。`,`你戴了一副新眼镜，显得斯文有礼。`,`你喷了点淡香水，周围的人似乎都注意到了。`];
    let msg = msgs[Math.floor(Math.random() * msgs.length)];
    if (anyImprove) log(msg);
    else log(msg + ' 但似乎没什么效果。');
    hidePanels();
    updateUI();
    advanceDay();
}

// 打工（随机效果）
function doWork(type) {
    let reward, stressInc, detChange, charmInc;
    if (type === 'easy') {
        reward = 50 + Math.floor(Math.random() * 80);
        stressInc = 2 + Math.floor(Math.random() * 6);
        detChange = Math.random() < 0.5 ? 1 : -1;
        charmInc = Math.random() < 0.3 ? 1 : 0;
    } else if (type === 'hard') {
        reward = 30 + Math.floor(Math.random() * 60);
        stressInc = 6 + Math.floor(Math.random() * 10);
        detChange = Math.random() < 0.7 ? -2 : 1;
        charmInc = Math.random() < 0.2 ? 1 : 0;
    } else if (type === 'tutor') {
        let baseProb = getAvgLevel() / 7;
        if (State.difficulty === 'hard') baseProb *= 0.6;
        let success = Math.random() < baseProb;
        if (success) {
            reward = 80 + Math.floor(Math.random() * 80);
            detChange = 2 + Math.floor(Math.random() * 3);
            charmInc = 1 + Math.floor(Math.random() * 2);
            stressInc = 3 + Math.floor(Math.random() * 5);
        } else {
            let fine = 60 + Math.floor(Math.random() * 60);
            ensureMoney(fine);
            State.determination = Math.max(0, State.determination - (3 + Math.floor(Math.random() * 4)));
            log('家教被投诉退款', `损失了${fine}元，决心下降`);
            hidePanels(); advanceDay(); return;
        }
    }
    if (State.difficulty === 'hard' && type !== 'tutor') {
        reward = Math.floor(reward * 0.7);
        stressInc = Math.floor(stressInc * 1.5);
        detChange = detChange * 2;
        charmInc = Math.floor(charmInc * 0.5);
    }
    State.money += reward;
    State.stress = Math.min(100, State.stress + stressInc);
    State.determination = Math.min(100, Math.max(0, State.determination + detChange));
    State.charm = Math.min(100, State.charm + charmInc);
    let workName = type==='easy'?'发传单':type==='hard'?'工地搬砖':'家教';
    const msgs = [`今天${workName}，挣了点辛苦钱。`, `今天${workName}，感觉身体被掏空。`, `今天${workName}，遇到了好心的老板。`, `今天${workName}，累得够呛。`, `今天${workName}，虽然累但收获不错。`, `今天${workName}，感觉腰酸背痛。`, `今天${workName}，赚了些零花钱。`, `今天${workName}，遇到了难缠的顾客，心累。`];
    log(msgs[Math.floor(Math.random() * msgs.length)]);
    hidePanels();
    advanceDay();
}

// 考试系统
function showExam(isGaokao = false) {
    let title = isGaokao ? "全国统一高考" : "月考";
    document.getElementById('exam-title').innerText = title;
    let thead = document.getElementById('exam-thead');
    let tbody = document.getElementById('exam-tbody');
    thead.innerHTML = '<tr><th>科目</th><th>得分</th></tr>';
    tbody.innerHTML = '';
    let totalScore = 0;
    let subjectScores = [];
    for (let sub of State.subjects) {
        let score = getScoreFromExp(sub.exp, sub.max);
        subjectScores.push({ name: sub.name, score: score, max: sub.max });
        totalScore += score;
    }
    let stressMod = 1 - (State.stress / 200);
    stressMod = Math.max(0.5, Math.min(1, stressMod));
    totalScore = Math.floor(totalScore * stressMod);
    let eventBonus = Math.floor(Math.random() * 31) - 15;
    totalScore += eventBonus;
    totalScore = Math.min(750, Math.max(0, totalScore));
    for (let s of subjectScores) {
        let row = document.createElement('tr');
        let finalScore = Math.floor(s.score * stressMod);
        let ratio = finalScore / s.max;
        let level = 'E';
        if (ratio >= 0.95) level = 'SSS';
        else if (ratio >= 0.9) level = 'SS';
        else if (ratio >= 0.85) level = 'S';
        else if (ratio >= 0.8) level = 'A';
        else if (ratio >= 0.7) level = 'B';
        else if (ratio >= 0.6) level = 'C';
        else if (ratio >= 0.5) level = 'D';
        let color = getLevelColor(level);
        row.innerHTML = `<td>${s.name}</td><td class="exam-cell" style="background:${color}; color:white; text-shadow:0 1px 2px black;">${finalScore}</td>`;
        tbody.appendChild(row);
    }
    let totalRow = document.createElement('tr');
    totalRow.innerHTML = `<td><strong>总分</strong></td><td class="exam-cell" style="background:var(--primary); color:white;"><strong>${totalScore}</strong></td>`;
    tbody.appendChild(totalRow);
    let rank = "", reward = 0;
    if (totalScore >= 680) { rank = "全省前100名"; reward = 1000; }
    else if (totalScore >= 650) { rank = "全省前500名"; reward = 500; }
    else if (totalScore >= 600) { rank = "全省前2000名"; reward = 300; }
    else if (totalScore >= 500) { rank = "全省前10000名"; reward = 150; }
    else { rank = "全省排名靠后"; reward = 50; }
    if (!isGaokao) {
        if (State.difficulty === 'hard') reward = Math.floor(reward * 0.5);
        State.money += reward;
        document.getElementById('exam-rewards').innerText = `奖励零花钱 ${reward} 元，预估排名：${rank}`;
    } else {
        let school = "";
        if (totalScore >= 680) school = "清华大学 / 北京大学";
        else if (totalScore >= 660) school = "复旦大学 / 上海交通大学 / 浙江大学";
        else if (totalScore >= 630) school = "南京大学 / 中国科学技术大学 / 西安交通大学";
        else if (totalScore >= 600) school = "哈尔滨工业大学 / 武汉大学 / 华中科技大学";
        else if (totalScore >= 550) school = "重庆大学 / 四川大学 / 电子科技大学";
        else if (totalScore >= 500) school = "重庆邮电大学 / 西南大学 / 合肥工业大学";
        else if (totalScore >= 450) school = "一本院校";
        else if (totalScore >= 400) school = "二本院校";
        else school = "专科院校 / 复读";
        document.getElementById('exam-rewards').innerHTML = `<strong>总分：${totalScore} 分</strong><br>录取学校：${school}<br>全省排名：${rank}`;
        window._gaokaoScore = totalScore;
        window._gaokaoSchool = school;
    }
    let cells = document.querySelectorAll('.exam-cell');
    cells.forEach((cell, idx) => setTimeout(() => cell.classList.add('pop'), idx * 100));
    document.getElementById('exam-close-btn').classList.remove('hidden');
    document.getElementById('exam-modal').classList.remove('hidden');
    if (isGaokao) {
        document.getElementById('exam-close-btn').onclick = () => {
            document.getElementById('exam-modal').classList.add('hidden');
            showGaokaoResult();
        };
    } else {
        document.getElementById('exam-close-btn').onclick = () => {
            document.getElementById('exam-modal').classList.add('hidden');
            advanceDay();
        };
    }
}
function showGaokaoResult() {
    State.isGraduated = true;
    let score = window._gaokaoScore || 0;
    let school = window._gaokaoSchool || "未知";
    let debtText = State.usuryLoan > 0 ? ` 高利贷 ${State.usuryLoan} 元未还。` : "";
    let marriageGirl = State.loves.find(l => l.dating && l.trueFeel >= 70) || State.loves.find(l => l.trueFeel >= 80);
    let marriageText = marriageGirl ? `💍 你和 ${marriageGirl.name} 终成眷属，步入了婚姻殿堂！` : '毕业后你独自一人，开始了新生活。';
    document.getElementById('gaokao-content').innerHTML = `<p>你的高考成绩：${score} 分</p><p>录取学校：${school}</p><p>${debtText}</p>`;
    document.getElementById('marriage-content').innerHTML = marriageText;
    document.getElementById('gaokao-modal').classList.remove('hidden');
}

// 随机事件函数（与之前相同，省略部分重复内容，但保证完整）
function triggerTeacherEvent() {
    State.teacherEventToday = true;
    let sub = State.subjects[Math.floor(Math.random() * State.subjects.length)];
    document.getElementById('teacher-question').innerHTML = `👩‍🏫 班主任提问 <strong>${sub.name}</strong> 问题！<br>当前等级: ${sub.level}`;
    window._currentTeacherSub = sub.id;
    document.getElementById('teacher-panel').classList.remove('hidden');
}
function handleTeacher(choice) {
    let subId = window._currentTeacherSub;
    let sub = State.subjects.find(s => s.id === subId);
    let idx = getLevelIndex(sub.level);
    let prob = 0.2 + idx * 0.08;
    if (State.difficulty === 'hard') prob *= 0.8;
    let rand = Math.random();
    if (choice === 'try') {
        if (rand < prob) {
            State.determination = Math.min(100, State.determination + 8);
            log(`成功回答${sub.name}问题`, '决心+8');
            State.loves.forEach(l => addTrueFeel(l.id, 2));
            log('同学们投来羡慕的目光');
        } else {
            State.determination = Math.max(0, State.determination - 5);
            State.stress = Math.min(100, State.stress + 15);
            log(`回答${sub.name}失败，被全班嘲笑`, '决心-5,压力+15');
            State.loves.forEach(l => addTrueFeel(l.id, -5));
            log('恋人们似乎有些失望');
        }
    } else {
        State.determination = Math.max(0, State.determination - 2);
        State.stress = Math.min(100, State.stress + 8);
        log(`罚站一节课`, '决心-2,压力+8');
    }
    hidePanels();
    updateUI();
    advanceDay();
}
let loveLetterAttempts = 0;
function triggerLoveLetterEvent() {
    let available = State.loves.filter(l => !l.dating);
    if (available.length === 0) return;
    loveLetterAttempts = 0;
    updateLoveLetterPanel();
    document.getElementById('loveletter-panel').classList.remove('hidden');
}
function updateLoveLetterPanel() {
    let cost = 50 + loveLetterAttempts * 50;
    let successProb = Math.max(0.1, 0.6 - loveLetterAttempts * 0.1);
    let deterLoss = 2 + loveLetterAttempts * 2;
    document.getElementById('loveletter-desc').innerHTML = `你在书桌里发现一封匿名情书……（第${loveLetterAttempts+1}次尝试，成本${cost}💰，成功率${Math.floor(successProb*100)}%，失败决心-${deterLoss}）`;
}
function handleLoveLetter(choice) {
    if (choice === 'find') {
        let cost = 50 + loveLetterAttempts * 50;
        ensureMoney(cost);
        let successProb = Math.max(0.1, 0.6 - loveLetterAttempts * 0.1);
        if (Math.random() < successProb) {
            let available = State.loves.filter(l => !l.dating);
            if (available.length === 0) { log(`你花${cost}元寻找，但所有人都已有对象，没找到送信人`); loveLetterAttempts++; updateLoveLetterPanel(); return; }
            let love = available[Math.floor(Math.random() * available.length)];
            addTrueFeel(love.id, 12);
            log(`你花${cost}元找到了送情书的人：${love.name}，对方害羞地跑开了`, `好感上升`);
            hidePanels(); updateUI(); advanceDay();
        } else {
            let deterLoss = 2 + loveLetterAttempts * 2;
            State.determination = Math.max(0, State.determination - deterLoss);
            log(`你花${cost}元寻找，没找到送信人，决心-${deterLoss}`, `💰-${cost}`);
            loveLetterAttempts++;
            updateLoveLetterPanel();
            return;
        }
    } else {
        State.determination = Math.max(0, State.determination - 5);
        log('你扔掉了情书', '决心-5');
        hidePanels(); updateUI(); advanceDay();
    }
}
function triggerSportsEvent() {
    document.getElementById('sports-desc').innerText = '体育课到了，你打算……';
    document.getElementById('sports-event-panel').classList.remove('hidden');
}
function handleSports(choice) {
    let reviewGain = 5, safeCharm = 1, safeStress = -3;
    if (State.difficulty === 'hard') { reviewGain = 3; safeCharm = 0; safeStress = -2; }
    if (choice === 'review') {
        let sub = State.subjects[Math.floor(Math.random() * State.subjects.length)];
        addSubjectExp(sub.id, reviewGain);
        log('体育课偷偷复习', `${sub.name}经验+${reviewGain}`);
    } else if (choice === 'safe') {
        State.charm = Math.min(100, State.charm + safeCharm);
        State.stress = Math.max(0, State.stress + safeStress);
        log('稳妥打球', `魅力+${safeCharm},压力${safeStress}`);
    } else if (choice === 'showoff') {
        let r = Math.random();
        if (r < 0.3) {
            State.charm = Math.max(0, State.charm - 5);
            State.stress = Math.min(100, State.stress + 15);
            State.determination = Math.max(0, State.determination - 3);
            log('秀操作失败', '魅力-5,压力+15,决心-3');
        } else if (r < 0.8) {
            State.charm = Math.min(100, State.charm + 5);
            State.stress = Math.max(0, State.stress - 8);
            State.determination = Math.min(100, State.determination + 3);
            log('秀操作成功', '魅力+5,压力-8,决心+3');
        } else {
            State.charm = Math.min(100, State.charm + 10);
            State.stress = Math.max(0, State.stress - 15);
            State.determination = Math.min(100, State.determination + 5);
            log('惊天大灌篮', '魅力+10,压力-15,决心+5');
        }
    }
    hidePanels();
    advanceDay();
}
function triggerConfession() {
    let candidates = State.loves.filter(l => !l.dating && !l.ex);
    if (candidates.length === 0) return false;
    let love = candidates[Math.floor(Math.random() * candidates.length)];
    window._confessionLove = love;
    document.getElementById('confession-desc').innerText = `${love.name}红着脸对你说：我……我喜欢你很久了！你怎么办？`;
    document.getElementById('confession-panel').classList.remove('hidden');
    return true;
}
function handleConfession(choice) {
    let love = window._confessionLove;
    if (choice === 'accept') {
        let cur = State.loves.filter(l => l.dating);
        if (cur.length > 0 && Math.random() < 0.5) { triggerCaught(cur[0], love); return; }
        love.dating = true;
        addTrueFeel(love.id, 15);
        log(`你接受了${love.name}的表白，对方非常开心`);
    } else {
        addTrueFeel(love.id, -10);
        log(`你拒绝了${love.name}的表白`);
    }
    hidePanels();
    updateUI();
    advanceDay();
}
function triggerCaught(oldLove, newLove) {
    let desc = `${oldLove.name}发现你和${newLove.name}在一起，大吵一架！`;
    document.getElementById('caught-desc').innerText = desc;
    document.getElementById('caught-panel').classList.remove('hidden');
    addTrueFeel(oldLove.id, -30);
    addTrueFeel(newLove.id, -30);
    oldLove.dating = false;
    newLove.dating = false;
    State.determination = Math.max(0, State.determination - 15);
    State.stress = Math.min(100, State.stress + 30);
    log(desc, '关系破裂');
    if (Math.random() < 0.01) triggerSuicide(oldLove);
}
function closeCaughtPanel() {
    document.getElementById('caught-panel').classList.add('hidden');
    updateUI();
    advanceDay();
}
function triggerSuicide(love) {
    State.determination = 0;
    State.stress = 100;
    State.money = 0;
    document.getElementById('suicide-desc').innerText = `${love.name}因分手想不开跳楼了！你陷入深深的自责……`;
    document.getElementById('suicide-panel').classList.remove('hidden');
}
function closeSuicidePanel() { location.reload(); }
function triggerParentEvent() {
    let hasDating = State.loves.some(l => l.dating);
    if (hasDating) {
        let love = State.loves.find(l => l.dating);
        if (Math.random() < 0.4) {
            love.dating = false;
            love.ex = true;
            addTrueFeel(love.id, -30);
            log(`父母强烈反对你和${love.name}交往，你们被迫分手`, '💔');
            document.getElementById('parent-desc').innerHTML = `父母在电话里严厉地说：“不许再和${love.name}来往！否则打断你的腿！”你无奈分手。`;
        } else {
            log(`父母打来电话，劝你以学业为重，不要早恋`, '压力+5');
            State.stress = Math.min(100, State.stress + 5);
            document.getElementById('parent-desc').innerHTML = `父母语重心长：“高考前专心学习，感情的事以后再说。”你压力增加了。`;
        }
    } else {
        log(`父母催你找对象：“隔壁老王儿子都带女朋友回家了，你怎么还没动静？”`, '压力+8');
        State.stress = Math.min(100, State.stress + 8);
        document.getElementById('parent-desc').innerHTML = `父母在电话里唠叨：“你也该找个人了，别光顾着学习！”你压力上升。`;
    }
    document.getElementById('parent-panel').classList.remove('hidden');
}
function closeParentPanel() {
    document.getElementById('parent-panel').classList.add('hidden');
    advanceDay();
}
function doStudy() {
    if (isWeekend()) { alert('周末学校不上课'); return; }
    let gains = {};
    State.subjects.forEach(s => {
        let gain = 4 + Math.floor(State.determination / 30) + State.facility;
        if (State.difficulty === 'hard') gain = Math.floor(gain * 0.7);
        addSubjectExp(s.id, gain);
        gains[s.name] = gain;
    });
    State.stress = Math.min(100, State.stress + 3);
    log('认真听课', `各科经验+${Math.min(...Object.values(gains))}~${Math.max(...Object.values(gains))},压力+3`);
    hidePanels();
    advanceDay();
}
function doTrain(subId) {
    let sub = State.subjects.find(s => s.id === subId);
    let price = TRAIN_PRICE[sub.level] || 50;
    ensureMoney(price);
    let gainBase = 12 + Math.floor(State.determination / 20) + State.facility * 2;
    if (State.difficulty === 'hard') gainBase = Math.floor(gainBase * 0.8);
    addSubjectExp(subId, gainBase);
    State.stress = Math.min(100, State.stress + 5);
    log(`魔鬼特训班 (${sub.name}) 花费 ${price}💰`, `经验+${gainBase},压力+5`);
    hidePanels();
    advanceDay();
}
function doRest() {
    State.stress = Math.max(0, State.stress - 12);
    log('好好休息', '压力-12');
    hidePanels();
    advanceDay();
}
function doSlack() {
    if (isWeekend()) { alert('周末不能摸鱼'); return; }
    let sub = State.subjects[Math.floor(Math.random() * State.subjects.length)];
    let gain = 2 + Math.floor(Math.random() * 3);
    addSubjectExp(sub.id, gain);
    State.stress = Math.max(0, State.stress - 2);
    log(`上课摸鱼，看了会${sub.name}杂书`, `经验+${gain},压力-2`);
    if (Math.random() < 0.3) { triggerPhoneConfiscation(); return; }
    hidePanels();
    advanceDay();
}
function triggerPhoneConfiscation() {
    let fine = 100;
    ensureMoney(fine);
    State.determination = Math.max(0, State.determination - 5);
    log('手机被没收', '罚款100,决心-5');
    hidePanels();
    advanceDay();
}
function closePhonePanel() {
    document.getElementById('phone-panel').classList.add('hidden');
    if (window._phoneCallback) { window._phoneCallback(); window._phoneCallback = null; }
}
function doDate(loveId) {
    let cost = Math.floor(Math.random() * 61) + 20;
    ensureMoney(cost);
    let love = getLove(loveId);
    if (love.dating) {
        let delta = addTrueFeel(loveId, 8);
        State.stress = Math.max(0, State.stress - 8);
        State.charm = Math.min(100, State.charm + 1);
        let msg = `和${love.name}约会 (花费${cost}💰)`;
        if (delta > 0) msg += '，对方非常开心';
        else msg += '，气氛有点微妙';
        log(msg, `压力-8,魅力+1`);
        hidePanels();
        advanceDay();
    } else {
        let prob = love.trueFeel / 100;
        if (Math.random() < prob) {
            let delta = addTrueFeel(loveId, 8);
            State.stress = Math.max(0, State.stress - 8);
            State.charm = Math.min(100, State.charm + 1);
            let msg = `和${love.name}约会 (花费${cost}💰)`;
            if (delta > 0) msg += '，对方非常开心';
            else msg += '，气氛有点微妙';
            log(msg, `压力-8,魅力+1`);
        } else {
            addTrueFeel(loveId, -3);
            log(`${love.name}拒绝了你 (花费${cost}💰打水漂)`, '真实好感下降');
        }
        hidePanels();
        advanceDay();
    }
}
function showStudyPanel() { if (isWeekend()) { alert('周末学校不上课'); return; } hidePanels(); doStudy(); }
function showTrainPanel() { hidePanels(); let html = ''; State.subjects.forEach(s => { let price = TRAIN_PRICE[s.level] || 50; html += `<button onclick="doTrain('${s.id}')">${s.name} (${price}💰)</button>`; }); document.getElementById('train-subjects').innerHTML = html; document.getElementById('train-panel').classList.remove('hidden'); }
function showDatePanel() { hidePanels(); let html = ''; State.loves.forEach(l => html += `<button onclick="doDate('${l.id}')">${l.name} (你认为的好感${Math.round(l.feel)})</button>`); document.getElementById('date-love').innerHTML = html; document.getElementById('date-panel').classList.remove('hidden'); }
function showWorkPanel() { hidePanels(); document.getElementById('work-panel').classList.remove('hidden'); }
function showLoanPanel() { hidePanels(); document.getElementById('panel-bank-loan').innerText = State.bankLoan; document.getElementById('panel-usury-loan').innerText = State.usuryLoan; let rate = State.difficulty === 'easy' ? 7 : 15; document.getElementById('usury-rate-panel').innerText = rate; let limit = State.difficulty === 'easy' ? 10000 : 6000; document.getElementById('bank-limit').innerText = limit; document.getElementById('loan-panel').classList.remove('hidden'); }
function showConfessionTo(loveId) { let love = getLove(loveId); if (!love) return; let cur = State.loves.filter(l => l.dating); if (cur.length > 0 && Math.random() < 0.5) { triggerCaught(cur[0], love); } else { let prob = love.trueFeel / 100; if (Math.random() < prob) { love.dating = true; addTrueFeel(loveId, 15); log(`你向${love.name}表白成功，对方害羞地答应了`); } else { addTrueFeel(loveId, -8); log(`你向${love.name}表白被拒绝，气氛尴尬`); } } hidePanels(); updateUI(); advanceDay(); }
function askForMoney(loveId) { let love = getLove(loveId); if (!love.isRich) return; if (love.trueFeel < 60) { alert('对方还不是你的恋人，不能要钱'); return; } if (love.askCount >= love.maxAsk) { alert('你们已经再无交集'); return; } let amt = 200 + Math.floor(Math.random() * 200); State.money += amt; addTrueFeel(loveId, -10); love.askCount++; log(`从${love.name}拿到 ${amt}元零花钱`, '对方有些不悦'); if (love.askCount >= love.maxAsk) log(`💔 你和${love.name}再无交集`, '缘尽'); updateUI(); }
function breakup(loveId) { let love = getLove(loveId); if (!love.dating) return; love.dating = false; love.ex = true; addTrueFeel(loveId, -20); log(`你和${love.name}分手了`, '对方看起来很伤心'); if (Math.random() < 0.005) triggerSuicide(love); updateUI(); }
function closeEventModal() { document.getElementById('event-modal').classList.add('hidden'); if (window._simpleEventCallback) { window._simpleEventCallback(); window._simpleEventCallback = null; updateUI(); } }
function studyStock() {
    let levelIndex = LEVELS.indexOf(stockLevel);
    let cost = 30 + levelIndex * 15;
    let stressInc = 5 + levelIndex * 2;
    ensureMoney(cost);
    State.stress = Math.min(100, State.stress + stressInc);
    let gain = 5 + Math.floor(Math.random() * 5);
    addStockExp(gain);
    log(`学习炒股 (花费${cost}💰, 压力+${stressInc})`, `炒股经验+${gain}`);
    hidePanels();
    advanceDay();
}

// 初始化女生
function initLoves() {
    let isMale = State.gender === 'male';
    let crushName = document.getElementById('name-crush')?.value.trim() || (isMale ? '柳如烟' : '林逸飞');
    let richName = document.getElementById('name-rich')?.value.trim() || (isMale ? '林薇薇' : '王思聪');
    let normal1Name = document.getElementById('name-normal1')?.value.trim() || (isMale ? '陈雨桐' : '张伟');
    let normal2Name = document.getElementById('name-normal2')?.value.trim() || (isMale ? '赵灵儿' : '李华');
    State.loves = [
        { id: 'crush', name: crushName, type: 'crush', isRich: false, trueFeel: Math.random() * 5, feel: 0, dating: false, ex: false, askCount: 0, maxAsk: 0 },
        { id: 'rich', name: richName, type: 'rich', isRich: true, trueFeel: Math.random() * 5, feel: 0, dating: false, ex: false, askCount: 0, maxAsk: Math.floor(Math.random() * 5) + 1 },
        { id: 'normal1', name: normal1Name, type: 'normal', isRich: false, trueFeel: Math.random() * 5, feel: 0, dating: false, ex: false },
        { id: 'normal2', name: normal2Name, type: 'normal', isRich: false, trueFeel: Math.random() * 5, feel: 0, dating: false, ex: false }
    ];
    State.loves.forEach(l => updateDisplayFeel(l));
}

// 性别切换（仅更新标签文字）
function updateGenderText() {
    let isMale = document.querySelector('input[name="gender"]:checked').value === 'male';
    State.gender = isMale ? 'male' : 'female';
    document.getElementById('char-name-title').innerHTML = isMale ? '为女生命名 (校花、富家千金已标注)' : '为男生命名 (校草、富二代已标注)';
    if (isMale) {
        document.getElementById('label-crush').innerHTML = '🌸 校花';
        document.getElementById('label-rich').innerHTML = '💎 千金';
        document.getElementById('label-normal1').innerHTML = '普通女生';
        document.getElementById('label-normal2').innerHTML = '普通女生';
    } else {
        document.getElementById('label-crush').innerHTML = '🌸 校草';
        document.getElementById('label-rich').innerHTML = '💎 富二代';
        document.getElementById('label-normal1').innerHTML = '普通男生';
        document.getElementById('label-normal2').innerHTML = '普通男生';
    }
}

function startGame(diff) {
    State.difficulty = diff;
    let days = parseInt(document.getElementById('start-days').value);
    if (isNaN(days) || days < 1) days = 200;
    State.daysLeft = days;
    State.weekday = 0;
    State.money = 0;
    State.determination = 50;
    State.stress = 20;
    State.charm = 60;
    State.bankLoan = 0;
    State.usuryLoan = 0;
    if (diff === 'hard') State.usuryLoan = 500;
    State.facility = 0;
    State.examCountdown = 30;
    State.subjects = JSON.parse(JSON.stringify(SUBJECTS));
    if (diff === 'easy') State.subjects.forEach(s => s.exp = 20);
    else State.subjects.forEach(s => s.exp = 0);
    State.subjects.forEach(s => s.level = getSubjectLevel(s.exp));
    stockExp = 0; stockLevel = 'E';
    initLoves();
    State.isGraduated = false;
    State.teacherEventToday = false;
    updateGrade();
    for (let i = 0; i < stocks.length; i++) State[`stock_${i}`] = 0;
    document.getElementById('start-overlay').classList.add('hidden');
    document.getElementById('main-header').classList.remove('hidden');
    document.getElementById('main-body').classList.remove('hidden');
    updateUI();
    log('🔁 重生回到高考前，这次一定要逆天改命！', '决心+10');
    State.determination += 10;
}

function updateUI() {
    document.getElementById('ui-days-left').innerText = State.daysLeft;
    document.getElementById('ui-weekday').innerText = getWeekdayName(State.weekday);
    document.getElementById('ui-money').innerText = Math.floor(State.money);
    document.getElementById('ui-determination').innerText = State.determination;
    document.getElementById('ui-stress').innerText = State.stress;
    document.getElementById('current-days').innerText = State.daysLeft;
    document.getElementById('current-weekday').innerText = getWeekdayName(State.weekday);
    document.getElementById('stat-charm').innerText = State.charm;
    document.getElementById('stat-determination').innerText = State.determination;
    document.getElementById('stat-stress').innerText = State.stress;
    document.getElementById('stat-money').innerText = Math.floor(State.money);
    document.getElementById('stat-bank-loan').innerText = Math.floor(State.bankLoan);
    document.getElementById('stat-usury-loan').innerText = Math.floor(State.usuryLoan);
    document.getElementById('fac-level').innerText = State.facility;
    document.getElementById('fac-bonus').innerText = State.facility * 5;
    let subHtml = '';
    State.subjects.forEach(s => { subHtml += `<div class="subject-card"><div class="subject-label">${s.name}</div><div class="subject-score" style="background:${getLevelColor(s.level)};">${s.level}</div><div class="subject-exp">${s.exp}/${LEVEL_THRESHOLD[LEVELS.indexOf(s.level)+1]||'MAX'}</div></div>`; });
    document.getElementById('subject-scores').innerHTML = subHtml;
    let lovesHtml = '';
    State.loves.forEach(l => {
        let cardClass = l.type === 'crush' ? 'crush-card' : (l.isRich ? 'rich-card' : 'normal-card');
        let heartWidth = (l.feel / 100) * 100;
        lovesHtml += `<div class="love-card ${cardClass}"><div class="love-name">${l.name}${l.isRich ? ' 💎' : ''}</div>${l.dating ? '<span class="dating-tag">恋爱中</span>' : ''}<div class="love-feel">你认为的好感: ${Math.round(l.feel)}</div><div class="heart-bar"><div class="heart-fill" style="width:${heartWidth}%;"></div></div><div class="button-group">`;
        if (l.isRich && l.trueFeel >= 60 && !l.dating && l.askCount < l.maxAsk) lovesHtml += `<button class="btn-rich" onclick="askForMoney('${l.id}')">💰 要零花钱</button>`;
        if (l.dating) lovesHtml += `<button class="btn-danger" onclick="breakup('${l.id}')">💔 分手</button>`;
        if (!l.dating && !l.ex) lovesHtml += `<button class="btn-love" onclick="showConfessionTo('${l.id}')">💕 表白</button>`;
        lovesHtml += `</div></div>`;
    });
    document.getElementById('social-panel').innerHTML = lovesHtml;
    updateActionButtons();
}

function updateActionButtons() {
    let grid = document.getElementById('action-buttons');
    let isWeekendDay = isWeekend();
    grid.innerHTML = '';
    let actions = [
        { icon: '📖', title: '认真听课', cost: '各科+少量 | 压力+2', action: 'showStudyPanel', weekendLock: true },
        { icon: '⚡', title: '魔鬼特训', cost: '价格随等级提升', action: 'showTrainPanel', weekendLock: false },
        { icon: '💖', title: '约会', cost: '随机20~80💰 | 好感↑ | 压力-3', action: 'showDatePanel', weekendLock: false },
        { icon: '🔨', title: '打工', cost: '赚钱 | 可能增减属性', action: 'showWorkPanel', weekendLock: false },
        { icon: '😴', title: '休息', cost: '压力-12', action: 'doRest', weekendLock: false },
        { icon: '🐟', title: '上课摸鱼', cost: '单科小经验 | 压力-2 | 可能没收手机', action: 'doSlack', weekendLock: true },
        { icon: '📈', title: '炒股', cost: '买卖股票 | 需炒股能力', action: 'showStockPanel', weekendLock: false },
        { icon: '📊', title: '学习炒股', cost: '花费随等级提升', action: 'studyStock', weekendLock: false },
        { icon: '💄', title: '提升形象', cost: '花钱提升所有女生好感', action: 'improveImage', weekendLock: false }
    ];
    actions.forEach(a => {
        let card = document.createElement('div');
        let isLocked = isWeekendDay && (a.weekendLock === true);
        card.className = `action-card ${isLocked ? 'weekend-locked' : ''}`;
        if (typeof a.action === 'string') {
            card.setAttribute('onclick', isLocked ? '' : `${a.action}()`);
        } else {
            card.setAttribute('onclick', isLocked ? '' : `(${a.action.toString()})()`);
        }
        card.innerHTML = `<div class="action-icon">${a.icon}</div><div class="action-title">${a.title}</div><div class="action-cost">${a.cost}</div>`;
        grid.appendChild(card);
    });
}

function advanceDay() {
    if (State.isGraduated) return;
    if (State.bankLoan > 0) {
        let interest = Math.floor(State.bankLoan * 0.01);
        if (interest < 1) interest = 1;
        State.bankLoan += interest;
        log(`银行贷款利息 ${interest} 元`, '💸');
    }
    if (State.usuryLoan > 0) {
        let rate = State.difficulty === 'easy' ? 0.07 : 0.15;
        let interest = Math.floor(State.usuryLoan * rate);
        if (interest < 1) interest = 1;
        State.usuryLoan += interest;
        log(`高利贷利息 ${interest} 元`, '💸');
    }
    State.daysLeft--;
    if (State.daysLeft <= 0) {
        if (checkSickBeforeGaokao()) return;
        showExam(true);
        return;
    }
    State.weekday = (State.weekday + 1) % 7;
    updateGrade();
    updateStocks();
    if (State.daysLeft % 30 === 0 && State.bankLoan > 0) {
        let total = State.bankLoan;
        if (State.money >= total) {
            State.money -= total;
            State.bankLoan = 0;
            log(`🏦 银行贷款到期，自动扣除 ${total} 元还清。`);
        } else {
            let need = total - State.money;
            State.usuryLoan += need;
            State.money = 0;
            State.bankLoan = 0;
            log(`🏦 银行贷款到期，零花钱不足，自动借高利贷 ${need} 元还清。`);
        }
    }
    State.examCountdown--;
    if (State.examCountdown <= 0) { State.examCountdown = 30; showExam(false); return; }
    if (!isWeekend()) {
        let eventProb = 0.15;
        if (State.difficulty === 'hard') eventProb = 0.08;
        if (!State.teacherEventToday && Math.random() < eventProb) { triggerTeacherEvent(); return; }
        if (Math.random() < eventProb) { triggerLoveLetterEvent(); return; }
        if (Math.random() < 0.03 && triggerConfession()) return;
        if (Math.random() < 0.05) { triggerSportsEvent(); return; }
        if (Math.random() < 0.08) { triggerParentEvent(); return; }
    }
    State.determination = Math.min(100, Math.max(0, State.determination));
    State.stress = Math.min(100, Math.max(0, State.stress));
    State.charm = Math.min(100, Math.max(0, State.charm));
    State.teacherEventToday = false;
    updateUI();
    if (State.stress >= 100) {
        alert('⚠️ 压力爆炸，你病倒了一周');
        State.stress = 40;
        for (let i = 0; i < 7; i++) {
            if (State.bankLoan > 0) {
                let interest = Math.floor(State.bankLoan * 0.01);
                if (interest < 1) interest = 1;
                State.bankLoan += interest;
            }
            if (State.usuryLoan > 0) {
                let rate = State.difficulty === 'easy' ? 0.07 : 0.15;
                let interest = Math.floor(State.usuryLoan * rate);
                if (interest < 1) interest = 1;
                State.usuryLoan += interest;
            }
            State.daysLeft--;
            if (State.daysLeft <= 0) {
                if (checkSickBeforeGaokao()) return;
                showExam(true);
                return;
            }
            State.weekday = (State.weekday + 1) % 7;
        }
        log('病倒一周', '😷 跳过7天，利息已计算');
        updateUI();
    }
}
function checkSickBeforeGaokao() {
    if (State.daysLeft <= 1 && State.stress >= 90) {
        document.getElementById('sick-gaokao-desc').innerHTML = `高考前你因压力过大病倒了，无法参加考试……`;
        document.getElementById('sick-gaokao-panel').classList.remove('hidden');
        return true;
    }
    return false;
}
function handleSickGaokao(choice) {
    document.getElementById('sick-gaokao-panel').classList.add('hidden');
    if (choice === 'retry') {
        let days = parseInt(document.getElementById('start-days').value);
        if (isNaN(days) || days < 1) days = 200;
        State.daysLeft = days;
        State.weekday = 0;
        State.money = 0;
        State.determination = 50;
        State.stress = 20;
        State.charm = 60;
        State.bankLoan = 0;
        State.usuryLoan = 0;
        if (State.difficulty === 'hard') State.usuryLoan = 500;
        State.facility = 0;
        State.examCountdown = 30;
        State.subjects = JSON.parse(JSON.stringify(SUBJECTS));
        if (State.difficulty === 'easy') State.subjects.forEach(s => s.exp = 20);
        else State.subjects.forEach(s => s.exp = 0);
        State.subjects.forEach(s => s.level = getSubjectLevel(s.exp));
        stockExp = 0; stockLevel = 'E';
        initLoves();
        State.isGraduated = false;
        State.teacherEventToday = false;
        updateGrade();
        for (let i = 0; i < stocks.length; i++) State[`stock_${i}`] = 0;
        updateUI();
        log('你选择了复读，重新出发！', '📖 新开始');
    } else {
        State.isGraduated = true;
        let scoreText = '你错过了高考，只能步入社会。';
        if (State.usuryLoan > 0) scoreText += ' 高利贷缠身，生活艰辛。';
        document.getElementById('gaokao-content').innerHTML = `<p>${scoreText}</p><p>高利贷: ${State.usuryLoan}元</p>`;
        document.getElementById('marriage-content').innerHTML = '独自面对人生。';
        document.getElementById('gaokao-modal').classList.remove('hidden');
    }
}

window.addEventListener('DOMContentLoaded', () => {
    updateGenderText();
    document.querySelectorAll('input[name="gender"]').forEach(r => r.addEventListener('change', updateGenderText));
});
window.startGame = startGame;
window.showStudyPanel = showStudyPanel; window.showTrainPanel = showTrainPanel; window.showDatePanel = showDatePanel; window.showWorkPanel = showWorkPanel; window.showLoanPanel = showLoanPanel; window.showStockPanel = showStockPanel; window.studyStock = studyStock; window.improveImage = improveImage;
window.doTrain = doTrain; window.doDate = doDate; window.doWork = doWork; window.doRest = doRest; window.doSlack = doSlack; window.hidePanels = function () { document.querySelectorAll('.sub-panel').forEach(p => p.classList.add('hidden')); };
window.handleTeacher = handleTeacher; window.handleLoveLetter = handleLoveLetter; window.closeEventModal = closeEventModal; window.askForMoney = askForMoney; window.closeExam = closeExam; window.takeBankLoan = takeBankLoan; window.takeUsuryLoan = takeUsuryLoan; window.repayAllBankLoan = repayAllBankLoan; window.repayAllUsuryLoan = repayAllUsuryLoan; window.repayBankLoanPartial = repayBankLoanPartial; window.repayUsuryLoanPartial = repayUsuryLoanPartial;
window.closePhonePanel = closePhonePanel; window.handleSports = handleSports; window.showConfessionTo = showConfessionTo; window.breakup = breakup; window.closeCaughtPanel = closeCaughtPanel; window.selectMarriage = selectMarriage; window.handleConfession = handleConfession; window.closeParentPanel = closeParentPanel; window.buyStock = buyStock; window.sellStock = sellStock; window.buyAllStock = buyAllStock; window.sellAllOneStock = sellAllOneStock; window.sellAllStocks = sellAllStocks; window.handleSickGaokao = handleSickGaokao;
function closeExam() { /* already defined */ }
function selectMarriage(lid) { /* already defined */ }
function restartGame() { location.reload(); }
</script>
</body>
</html>
