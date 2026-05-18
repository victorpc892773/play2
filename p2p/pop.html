(function () {
  var ENABLED = true;
  var URL_POP = "//runative-syndicate.com/api/v1/direct/e15a176b286b4cf0af5b249fa8f873c9";
  var pageTitle = document.title || window.location.href;

  // ─── Estilos do console ───────────────────────────────────────────────────
  var styles = {
    header:   "color:#a78bfa; font-weight:bold; font-size:11px; background:#1e1b4b; padding:2px 6px; border-radius:3px;",
    success:  "color:#4ade80; font-weight:bold;",
    error:    "color:#f87171; font-weight:bold;",
    info:     "color:#60a5fa; font-weight:bold;",
    fire:     "color:#fb923c; font-weight:bold;",
    reset:    "color:#94a3b8; font-weight:normal;",
    label:    "color:#e2e8f0; font-weight:bold;",
    muted:    "color:#64748b; font-weight:normal; font-size:10px;",
    cyan:     "color:#22d3ee; font-weight:bold;",
    yellow:   "color:#fbbf24; font-weight:bold;",
  };

  // ─── Helpers de log ───────────────────────────────────────────────────────
  function logBanner() {
    console.log(
      "%c🎯 POP ENGINE  %cv1.0 ",
      styles.header,
      "color:#7c3aed; font-weight:bold; font-size:11px; background:#2e1065; padding:2px 6px; border-radius:3px;"
    );
  }

  function logStatus() {
    if (ENABLED) {
      console.log(
        "%c✅ Status    %cAtivado    %c📄 Página: %c" + pageTitle,
        styles.success, styles.label, styles.muted, styles.reset
      );
    } else {
      console.log(
        "%c❌ Status    %cDesativado %c📄 Página: %c" + pageTitle,
        styles.error, styles.label, styles.muted, styles.reset
      );
    }
  }

  function logFired() {
    console.log(
      "%c🚀 Disparado  %c→ Popup aberto   %c📄 " + pageTitle,
      styles.fire, styles.cyan, styles.muted
    );
    console.log(
      "%c⏳ Cooldown   %c15s até reativação",
      styles.yellow, styles.reset
    );
  }

  function logReady() {
    console.log(
      "%c🔄 Reativado  %c→ Aguardando próximo clique   %c📄 " + pageTitle,
      styles.success, styles.reset, styles.muted
    );
  }

  function logInit() {
    console.log(
      "%c🛡️  Overlay    %cMontado e escutando eventos",
      styles.info, styles.reset
    );
  }

  // ─── Inicialização ────────────────────────────────────────────────────────
  logBanner();
  logStatus();
  if (!ENABLED) return;

  function init() {
    var popupLoaded = false;
    var overlay = document.createElement('div');
    overlay.style.cssText = 'position:fixed;top:0;left:0;width:100%;height:100%;z-index:9999;';
    document.body.appendChild(overlay);
    logInit();

    function onTouch() {
      if (popupLoaded) return;
      popupLoaded = true;
      overlay.style.pointerEvents = 'none';
      window.open(URL_POP, "_blank");
      logFired();

      setTimeout(() => {
        popupLoaded = false;
        overlay.style.pointerEvents = 'auto';
        logReady();
      }, 15000);
    }

    overlay.addEventListener('mousedown', onTouch);
    overlay.addEventListener('touchend', onTouch, { passive: true });
  }

  if (document.body) {
    init();
  } else {
    document.addEventListener('DOMContentLoaded', init);
  }
})();
