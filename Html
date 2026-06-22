# quiz-economy-politics
<!-- Google Fonts (フォント読込) -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700;900&family=Outfit:wght@300;400;600;800&display=swap" rel="stylesheet">

<!-- Background Glow Effects -->
<div class="glow-bg">
    <div class="glow-sphere sphere-1"></div>
    <div class="glow-sphere sphere-2"></div>
</div>

<!-- App Container -->
<div class="container">
    <!-- Header -->
    <header class="header">
        <div class="logo">
            <span class="logo-spark">⚖️</span>
            <h1>CivicsQuiz Master</h1>
            <span class="badge-sub">公民</span>
        </div>
        <div class="theme-toggle-wrapper">
            <button id="themeToggleBtn" class="theme-toggle-btn" aria-label="テーマ切り替え">
                <svg class="sun-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.93 4.93l1.41 1.41M17.66 17.66l1.41 1.41M2 12h2M20 12h2M6.34 17.66l-1.41 1.41M19.07 4.93l-1.41 1.41"/></svg>
                <svg class="moon-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"/></svg>
            </button>
        </div>
    </header>

    <!-- Main Workspace -->
    <main class="main-content">
        
        <!-- 1. Dashboard View (Initial State) -->
        <section class="view-panel active-view" id="dashboardView">
            <div class="hero-section">
                <p class="hero-tagline">動かして、解いて、定着させる</p>
                <h2 class="hero-title">社会科4択クイズマスター</h2>
                <p class="hero-description">
                    大学別の対策を行うことができます
                </p>
            </div>

            <div class="dashboard-grid">
                <!-- Left: Stats Panel -->
                <div class="stats-panel glass-panel">
                    <h3>🏆 マイデータ (学習状況)</h3>
                    <div class="stats-list">
                        <div class="stat-card">
                            <span class="stat-label">ハイスコア (最高点)</span>
                            <span class="stat-value" id="statsHighScore">0</span>
                            <span class="stat-unit">点</span>
                        
                        </div>
                        <div class="stat-card">
                            <span class="stat-label">クイズ挑戦回数</span>
                            <span class="stat-value" id="statsAttempts">0</span>
                            <span class="stat-unit">回</span>
                        </div>
                        <div class="stat-card">
                            <span class="stat-label">正答率 (平均)</span>
                            <span class="stat-value" id="statsAccuracy">0</span>
                            <span class="stat-unit">%</span>
                        </div>
                    </div>
                    <button class="btn-reset-stats" id="btnResetStats">統計をリセットする</button>
                </div>

                <!-- Right: Setup Panel -->
                <div class="setup-panel glass-panel">
                    <h3>⚙️ クイズ設定</h3>

                    
                    <!-- Mode Selector -->
                    <div class="setup-group">
                        <label class="group-title">1. クイズモード</label>
                        <div class="mode-select-grid">
                            <button class="mode-btn active" data-mode="quick">
                                <span class="mode-icon">⚡</span>
                                <div class="mode-info">
                                    <strong>ランダム5問</strong>
                                    <p>気軽に行う実力チェック</p>
                                </div>
                            </button>
                            <button class="mode-btn" data-mode="marathon">
                                <span class="mode-icon">🏃</span>
                                <div class="mode-info">
                                    <strong>全問マラソン</strong>
                                    <p>収録されたすべての問題に挑戦</p>
                                </div>
                            </button>
                        </div>
                    </div>

                    <!-- Category Selector -->
                    <div class="setup-group">
                        <label class="group-title">2. 分野 (カテゴリ) フィルター</label>
                        <div class="category-select-list" id="categoryFilterContainer">
                            <button class="cat-pill active" data-category="all">すべて</button>
                        </div>
                    </div>

                    <!-- Timer Settings -->
                    <div class="setup-group">
                        <div class="timer-setting-row">
                            <div class="timer-info">
                                <strong class="group-title">3. 制限時間タイマー (1問20秒)</strong>
                                <p>緊張感を持って解きたい時におすすめです</p>
                            </div>
                            <label class="switch">
                                <input type="checkbox" id="timerToggleCheckbox" checked>
                                <span class="slider round"></span>
                            </label>
                        </div>
                    </div>

                    <!-- Action Button -->
                    <button class="primary-btn start-quiz-big" id="btnStartQuiz">
                        クイズを開始する
                    </button>
                </div>
            </div>
        </section>

        <!-- 2. Quiz Play View -->
        <section class="view-panel hidden" id="quizPlayView">
            <div class="quiz-play-layout">
                <!-- Progress Bar and Timer -->
                <div class="quiz-top-bar glass-panel">
                    <div class="quiz-meta-row">
                        <span class="quiz-category-badge" id="playCategoryBadge">分野</span>
                        <span class="quiz-progress-text">問題 <span id="playCurrentIndex">1</span> / <span id="playTotalCount">5</span></span>
                    </div>
                    <!-- Timer Line -->
                    <div class="timer-bar-container" id="timerBarContainer">
                        <div class="timer-bar-fill" id="timerBarFill"></div>
                    </div>
                </div>

                <!-- Question Container -->
                <div class="quiz-body-card glass-panel">
                    <h3 class="quiz-question-text" id="playQuestionText">
                        問題文がここにロードされます。
                    </h3>
                    
                    <div class="quiz-options-list">
                        <button class="play-option-btn" data-index="0">
                            <span class="option-num">1</span>
                            <span class="option-content">選択肢A</span>
                        </button>
                        <button class="play-option-btn" data-index="1">
                            <span class="option-num">2</span>
                            <span class="option-content">選択肢B</span>
                        </button>
                        <button class="play-option-btn" data-index="2">
                            <span class="option-num">3</span>
                            <span class="option-content">選択肢C</span>
                        </button>
                        <button class="play-option-btn" data-index="3">
                            <span class="option-num">4</span>
                            <span class="option-content">選択肢D</span>
                        </button>
                    </div>
                    
                    <div class="keyboard-hint">
                        ⌨️ キーボードの [1] [2] [3] [4] キーでも回答できます
                    </div>
                </div>
            </div>
        </section>

        <!-- 3. Answer Feedback View -->
        <section class="view-panel hidden" id="quizFeedbackView">
            <div class="quiz-feedback-layout">
                <div class="feedback-result-card glass-panel">
                    <div class="result-indicator" id="feedbackIndicator">
                        <span class="result-symbol" id="feedbackSymbol">⭕</span>
                        <h2 class="result-text" id="feedbackTitleText">正解！</h2>
                    </div>

                    <div class="explanation-content">
                        <h4>💡 詳細解説</h4>
                        <p id="feedbackExplanationText">詳しい説明がここに入ります。</p>
                    </div>
                    
                    <button class="primary-btn next-quiz-btn" id="btnNextQuestion">
                        次の問題へ ➔
                    </button>
                </div>
            </div>
        </section>

        <!-- 4. Result View -->
        <section class="view-panel hidden" id="quizResultView">
            <div class="quiz-result-layout">
                <div class="result-summary-card glass-panel">
                    <div class="result-trophy">🏆</div>
                    <h2>クイズ修了！</h2>
                    
                    <div class="result-score-block">
                        <div class="score-display">
                            <span class="score-num" id="resultScore">0</span>
                            <span class="score-max"> / <span id="resultMaxScore">100</span> 点</span>
                        </div>
                        <p class="accuracy-text">正答率: <span id="resultAccuracy">0</span>% (<span id="resultCorrectCount">0</span>問正解 / <span id="resultTotalQuestions">5</span>問中)</p>
                    </div>

                    <p class="evaluation-message" id="resultEvaluationText">
                        素晴らしい成績です！この調子で公民の基本をマスターしましょう。
                    </p>

                    <div class="result-action-buttons">
                        <button class="primary-btn" id="btnRestartQuiz">同じ条件でリトライ</button>
                        <button class="secondary-btn" id="btnGoToReview">📋 解答を復習する</button>
                        <button class="text-link-btn" id="btnBackToDashboard">ダッシュボードへ戻る</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. Detailed Review View -->
        <section class="view-panel hidden" id="quizReviewView">
            <div class="panel-header">
                <h2>📋 今回のテストの復習</h2>
                <p>正解した問題も間違えた問題も、解説を読んでしっかりと理解を定着させましょう。</p>
            </div>

            <div class="review-layout">
                <div class="review-items-container" id="reviewItemsContainer"></div>
                <div class="review-footer-actions">
                    <button class="primary-btn" id="btnReviewBackDashboard">ダッシュボードへ戻る</button>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2026 CivicsQuiz Master. Created by Antigravity.</p>
    </footer>
</div>
