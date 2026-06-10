/* ==========================================
   1. GLOBAL STYLES & VARIABLES
   ========================================== */
:root {
    --primary-color: #2563eb;
    --primary-hover: #1d4ed8;
    --bg-color: #f1f5f9;
    --card-bg: #ffffff;
    --text-color: #1e293b;
    --text-muted: #64748b;
    --border-color: #cbd5e1;
    --success-color: #16a34a;
    --radius: 16px;
    --transition: all 0.25s ease;
}

* { 
    box-sizing: border-box; 
    margin: 0; 
    padding: 0; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; 
}

body { 
    background-color: var(--bg-color); 
    color: var(--text-color); 
    display: flex; 
    justify-content: center; 
    align-items: center; 
    min-height: 100vh; 
    padding: 12px; 
}

/* ==========================================
   2. APP WRAPPER & CONTAINER
   ========================================== */
.app-container { 
    width: 100%; 
    max-width: 420px; 
    background: var(--card-bg); 
    border-radius: var(--radius); 
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08); 
    padding: 24px; 
    min-height: 520px; 
    display: flex; 
    flex-direction: column; 
    position: relative; 
    overflow: hidden;
}

.app-header { 
    text-align: center; 
    padding-bottom: 12px; 
    border-bottom: 1px solid #f1f5f9; 
    margin-bottom: 20px; 
}

.logo { 
    font-size: 1.5rem; 
    font-weight: 800; 
    letter-spacing: -0.5px;
}

.logo span { 
    color: var(--primary-color); 
}

/* ==========================================
   3. VIEW CONTROLLER (DYNAMIC SCREENS)
   ========================================== */
.app-view { 
    display: none; 
    animation: fadeIn 0.3s ease-in-out;
}

.app-view.active { 
    display: block; 
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(8px); }
    to { opacity: 1; transform: translateY(0); }
}

.back-nav { 
    cursor: pointer; 
    color: var(--primary-color); 
    margin-bottom: 15px; 
    font-weight: 600; 
    font-size: 0.9rem;
    display: inline-block;
}

/* ==========================================
   4. LOAN CALCULATOR CARD
   ========================================== */
.calculator-card { 
    background: #f8fafc; 
    border: 1px solid #e2e8f0;
    border-radius: var(--radius); 
    padding: 18px; 
    margin-bottom: 20px; 
}

.input-group { 
    margin-bottom: 18px; 
}

.label-row { 
    display: flex; 
    justify-content: space-between; 
    font-weight: 600; 
    font-size: 0.85rem; 
    margin-bottom: 6px; 
}

input[type="range"] { 
    width: 100%; 
    height: 6px;
    background: #e2e8f0;
    border-radius: 3px;
    outline: none;
    accent-color: var(--primary-color);
    margin: 8px 0;
}

.range-limits { 
    display: flex; 
    justify-content: space-between; 
    font-size: 0.75rem; 
    color: var(--text-muted); 
    font-weight: 500;
}

.result-box { 
    background: var(--card-bg); 
    padding: 12px; 
    text-align: center; 
    margin-bottom: 15px; 
    border-radius: 8px; 
    border: 1px dashed var(--border-color);
}

.result-value { 
    font-size: 1.5rem; 
    font-weight: 700; 
    color: var(--primary-color); 
    margin-top: 2px;
}

/* ==========================================
   5. BUTTONS & UTILITIES
   ========================================== */
.btn { 
    padding: 14px; 
    border-radius: 10px; 
    font-weight: 600; 
    font-size: 0.95rem;
    border: none; 
    cursor: pointer; 
    transition: var(--transition);
    text-align: center;
}

.btn-primary { 
    background: var(--primary-color); 
    color: white; 
}

.btn-primary:hover { 
    background: var(--primary-hover); 
}

.btn-secondary { 
    background: #e2e8f0; 
    color: var(--text-color); 
}

.btn-secondary:hover {
    background: #cbd5e1;
}

.btn-block { 
    width: 100%; 
}

.btn-group { 
    display: grid; 
    grid-template-columns: 1fr 2fr; 
    gap: 12px; 
    margin-top: 20px; 
}

/* ==========================================
   6. FORMS & LAYOUT FIELDS
   ========================================== */
.form-group { 
    margin-bottom: 16px; 
}

.form-row { 
    display: grid; 
    grid-template-columns: 1fr 1fr; 
    gap: 12px; 
    margin-bottom: 4px;
}

label { 
    font-size: 0.8rem; 
    font-weight: 600; 
    display: block; 
    margin-bottom: 6px; 
    color: #475569;
}

input[type="text"], 
input[type="number"], 
input[type="email"], 
input[type="password"], 
select { 
    width: 100%; 
    padding: 12px; 
    border: 1px solid var(--border-color); 
    border-radius: 8px; 
    outline: none; 
    font-size: 0.95rem;
    color: var(--text-color);
    background-color: #fff;
    transition: var(--transition);
}

input:focus, select:focus {
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}

/* Phone Field Structure */
.phone-input-wrapper { 
    display: flex; 
    border: 1px solid var(--border-color); 
    border-radius: 8px; 
    background: white; 
    overflow: hidden;
}

.phone-input-wrapper .prefix { 
    background: #f1f5f9; 
    padding: 12px; 
    font-size: 0.9rem; 
    font-weight: 600;
    border-right: 1px solid var(--border-color);
    display: flex;
    align-items: center;
}

.phone-input-wrapper input { 
    border: none; 
    padding: 12px; 
    width: 100%; 
    outline: none; 
    font-size: 0.95rem;
}

/* ==========================================
   7. SUMMARIES, OTP & DASHBOARD SPECIFICS
   ========================================== */
.summary-box { 
    background: #f8fafc; 
    border: 1px dashed var(--border-color); 
    padding: 14px; 
    border-radius: 8px; 
    margin: 20px 0; 
}

.summary-item { 
    display: flex; 
    justify-content: space-between; 
    font-size: 0.85rem; 
    margin-bottom: 6px; 
}

.summary-item:last-child {
    margin-bottom: 0;
}

/* OTP Boxes Container */
.otp-inputs { 
    display: flex; 
    justify-content: center; 
    gap: 12px; 
    margin: 20px 0; 
}

.otp-box { 
    width: 48px; 
    height: 48px; 
    text-align: center; 
    font-size: 1.3rem; 
    font-weight: 700; 
    border: 1px solid var(--border-color); 
    border-radius: 8px; 
    outline: none;
}

/* Dashboard Metrics Banner */
.success-banner { 
    background: #dcfce7; 
    color: var(--success-color); 
    padding: 12px; 
    border-radius: 8px; 
    font-weight: 600;
}

.approved-amount-card { 
    background: var(--primary-color); 
    color: white; 
    padding: 24px 15px; 
    border-radius: var(--radius); 
}

.features-grid { 
    display: grid; 
    grid-template-columns: repeat(3, 1fr); 
    gap: 8px; 
    text-align: center; 
    margin-top: 15px; 
}

.feature-item h4 {
    font-size: 0.8rem;
    margin: 3px 0 1px 0;
}

.feature-item p {
    font-size: 0.7rem;
}

/* ==========================================
   8. LOADING OVERLAY MODAL SYSTEM
   ========================================== */
.overlay { 
    position: absolute; 
    top: 0; 
    left: 0; 
    width: 100%; 
    height: 100%; 
    background: rgba(255, 255, 255, 0.95); 
    display: flex; 
    justify-content: center; 
    align-items: center; 
    border-radius: var(--radius); 
    z-index: 100;
}

.overlay.hidden { 
    display: none; 
}

.loader-circle { 
    width: 36px; 
    height: 36px; 
    border: 3.5px solid #e2e8f0; 
    border-top: 3.5px solid var(--primary-color); 
    border-radius: 50%; 
    animation: spin 0.8s linear infinite; 
}

@keyframes spin { 
    0% { transform: rotate(0deg); } 
    100% { transform: rotate(360deg); } 
}

.app-footer { 
    text-align: center; 
    color: var(--text-muted); 
    font-size: 0.7rem; 
    margin-top: auto; 
    padding-top: 20px; 
    border-top: 1px solid #f1f5f9;
}
