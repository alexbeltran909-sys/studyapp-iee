<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="StudyApp IEE">
<meta name="theme-color" content="#0F6E56">
<title>StudyApp — Ingeniería Ejecución Eléctrica</title>
<style>
:root {
  --green: #0F6E56; --green-l: #E1F5EE; --green-d: #04342C;
  --blue: #185FA5; --blue-l: #E6F1FB; --blue-d: #042C53;
  --red: #A32D2D; --red-l: #FCEBEB;
  --amber: #854F0B; --amber-l: #FAEEDA;
  --gray: #5F5E5A; --gray-l: #F1EFE8;
  --text: #1a1a1a; --text2: #666; --border: #e0e0e0;
  --bg: #f8f8f6; --card: #ffffff;
  --radius: 12px; --radius-sm: 8px;
}
* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: var(--bg); color: var(--text); min-height: 100vh; }
.screen { display: none; min-height: 100vh; padding-bottom: 80px; }
.screen.active { display: block; }

/* NAV */
.top-nav { background: var(--green); color: white; padding: 16px 20px 12px; display: flex; align-items: center; gap: 12px; position: sticky; top: 0; z-index: 100; }
.top-nav .back-btn { background: rgba(255,255,255,0.2); border: none; color: white; width: 36px; height: 36px; border-radius: 50%; font-size: 18px; cursor: pointer; display: flex; align-items: center; justify-content: center; }
.top-nav h1 { font-size: 18px; font-weight: 600; flex: 1; }
.top-nav .nav-icon { font-size: 22px; }
.bottom-nav { position: fixed; bottom: 0; left: 0; right: 0; background: white; border-top: 1px solid var(--border); display: flex; z-index: 100; padding-bottom: env(safe-area-inset-bottom); }
.bnav-btn { flex: 1; padding: 10px 4px 8px; border: none; background: none; color: var(--text2); font-size: 10px; cursor: pointer; display: flex; flex-direction: column; align-items: center; gap: 3px; transition: color 0.2s; }
.bnav-btn .icon { font-size: 22px; }
.bnav-btn.active { color: var(--green); }

/* HOME */
.home-header { background: linear-gradient(135deg, var(--green) 0%, #1D9E75 100%); color: white; padding: 32px 20px 28px; }
.home-header h2 { font-size: 26px; font-weight: 700; margin-bottom: 4px; }
.home-header p { font-size: 14px; opacity: 0.85; }
.section-label { font-size: 12px; font-weight: 600; color: var(--text2); text-transform: uppercase; letter-spacing: 0.5px; padding: 20px 20px 8px; }
.ramo-card { background: var(--card); margin: 0 16px 12px; border-radius: var(--radius); border: 1px solid var(--border); padding: 16px; display: flex; align-items: center; gap: 14px; cursor: pointer; transition: box-shadow 0.2s; }
.ramo-card:active { opacity: 0.8; }
.ramo-icon { width: 48px; height: 48px; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 24px; flex-shrink: 0; }
.ramo-card h3 { font-size: 15px; font-weight: 600; margin-bottom: 2px; }
.ramo-card p { font-size: 12px; color: var(--text2); }
.ramo-arrow { margin-left: auto; color: var(--text2); font-size: 18px; }
.add-card { background: var(--gray-l); border: 2px dashed var(--border); margin: 0 16px 12px; border-radius: var(--radius); padding: 16px; display: flex; align-items: center; gap: 14px; cursor: pointer; }
.add-card span { font-size: 14px; color: var(--text2); }

/* RAMO SCREEN */
.ramo-hero { padding: 24px 20px 20px; }
.ramo-hero h2 { font-size: 22px; font-weight: 700; margin-bottom: 4px; }
.ramo-hero p { font-size: 13px; color: var(--text2); }
.module-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; padding: 0 16px 16px; }
.module-card { background: var(--card); border-radius: var(--radius); border: 1px solid var(--border); padding: 18px 14px; cursor: pointer; transition: box-shadow 0.2s; }
.module-card:active { opacity: 0.8; }
.module-card .m-icon { font-size: 28px; margin-bottom: 8px; }
.module-card h4 { font-size: 14px; font-weight: 600; margin-bottom: 3px; }
.module-card p { font-size: 11px; color: var(--text2); line-height: 1.4; }
.module-card.green { border-left: 3px solid var(--green); }
.module-card.blue { border-left: 3px solid var(--blue); }
.module-card.amber { border-left: 3px solid #EF9F27; }
.module-card.red { border-left: 3px solid var(--red); }

/* CONTENT */
.content-wrap { padding: 16px; }
.topic-card { background: var(--card); border-radius: var(--radius); border: 1px solid var(--border); margin-bottom: 12px; overflow: hidden; }
.topic-header { padding: 14px 16px; display: flex; align-items: center; justify-content: space-between; cursor: pointer; }
.topic-header h3 { font-size: 15px; font-weight: 600; }
.topic-header .chevron { transition: transform 0.2s; color: var(--text2); }
.topic-header.open .chevron { transform: rotate(180deg); }
.topic-body { padding: 0 16px 16px; display: none; }
.topic-body.show { display: block; }
.topic-body p { font-size: 14px; line-height: 1.7; color: var(--text); margin-bottom: 8px; }
.tag { display: inline-block; font-size: 11px; padding: 3px 8px; border-radius: 20px; margin: 2px; }
.tag-g { background: var(--green-l); color: var(--green-d); }
.tag-b { background: var(--blue-l); color: var(--blue-d); }
.tag-r { background: var(--red-l); color: var(--red); }
.tag-a { background: var(--amber-l); color: var(--amber); }
.info-box { border-radius: var(--radius-sm); padding: 12px 14px; margin: 8px 0; font-size: 13px; line-height: 1.6; }
.info-green { background: var(--green-l); color: var(--green-d); border-left: 3px solid var(--green); }
.info-blue { background: var(--blue-l); color: var(--blue-d); border-left: 3px solid var(--blue); }
.info-amber { background: var(--amber-l); color: var(--amber); border-left: 3px solid #EF9F27; }
.info-red { background: var(--red-l); color: var(--red); border-left: 3px solid var(--red); }
.data-table { width: 100%; border-collapse: collapse; font-size: 13px; margin: 8px 0; }
.data-table th { background: var(--green); color: white; padding: 8px 10px; text-align: center; font-size: 12px; }
.data-table td { padding: 7px 10px; border-bottom: 1px solid var(--border); text-align: center; }
.data-table tr:nth-child(even) td { background: var(--gray-l); }

/* FLASHCARDS */
.fc-wrap { padding: 16px; }
.fc-progress { display: flex; align-items: center; gap: 8px; margin-bottom: 16px; }
.fc-bar { flex: 1; height: 6px; background: var(--border); border-radius: 3px; }
.fc-fill { height: 100%; background: var(--green); border-radius: 3px; transition: width 0.3s; }
.fc-count { font-size: 13px; color: var(--text2); white-space: nowrap; }
.card-scene { perspective: 1000px; height: 260px; margin-bottom: 16px; }
.card-3d { width: 100%; height: 100%; position: relative; transform-style: preserve-3d; transition: transform 0.5s; cursor: pointer; }
.card-3d.flipped { transform: rotateY(180deg); }
.card-face { position: absolute; width: 100%; height: 100%; backface-visibility: hidden; border-radius: var(--radius); display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 24px; text-align: center; }
.card-front { background: var(--green); color: white; }
.card-back { background: var(--card); border: 1px solid var(--border); transform: rotateY(180deg); }
.card-front .label { font-size: 11px; opacity: 0.7; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px; }
.card-front .question { font-size: 17px; font-weight: 600; line-height: 1.4; }
.card-back .answer { font-size: 16px; font-weight: 600; color: var(--green); margin-bottom: 8px; line-height: 1.4; }
.card-back .explain { font-size: 13px; color: var(--text2); line-height: 1.5; }
.tap-hint { font-size: 12px; color: var(--text2); text-align: center; margin-bottom: 16px; }
.fc-btns { display: flex; gap: 10px; }
.fc-btn { flex: 1; padding: 14px; border: none; border-radius: var(--radius-sm); font-size: 14px; font-weight: 600; cursor: pointer; }
.fc-btn-no { background: var(--red-l); color: var(--red); }
.fc-btn-yes { background: var(--green-l); color: var(--green); }
.fc-btn-next { background: var(--blue-l); color: var(--blue); flex: 1; }
.fc-result { text-align: center; padding: 32px 16px; }
.fc-result .big { font-size: 52px; font-weight: 700; color: var(--green); }
.fc-result p { color: var(--text2); font-size: 15px; margin-top: 8px; }
.fc-result button { margin-top: 24px; background: var(--green); color: white; border: none; border-radius: var(--radius-sm); padding: 14px 32px; font-size: 15px; font-weight: 600; cursor: pointer; }

/* EXAM */
.exam-wrap { padding: 16px; }
.exam-q { background: var(--card); border-radius: var(--radius); border: 1px solid var(--border); padding: 18px; margin-bottom: 12px; }
.exam-q .q-num { font-size: 11px; color: var(--text2); text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 8px; }
.exam-q .q-text { font-size: 15px; font-weight: 600; line-height: 1.5; margin-bottom: 16px; }
.opt-btn { width: 100%; text-align: left; background: var(--bg); border: 1px solid var(--border); border-radius: var(--radius-sm); padding: 12px 14px; margin-bottom: 8px; font-size: 14px; cursor: pointer; display: flex; gap: 10px; align-items: flex-start; line-height: 1.4; }
.opt-btn .opt-l { font-weight: 600; min-width: 18px; color: var(--text2); }
.opt-btn.correct { background: var(--green-l); border-color: var(--green); color: var(--green-d); }
.opt-btn.wrong { background: var(--red-l); border-color: var(--red); color: var(--red); }
.opt-btn.disabled { opacity: 0.5; pointer-events: none; }
.opt-fb { font-size: 13px; padding: 10px 12px; border-radius: var(--radius-sm); margin-top: 8px; line-height: 1.5; }
.exam-next { width: 100%; background: var(--green); color: white; border: none; border-radius: var(--radius-sm); padding: 14px; font-size: 15px; font-weight: 600; cursor: pointer; margin-top: 8px; }
.score-screen { text-align: center; padding: 32px 20px; }
.score-big { font-size: 64px; font-weight: 700; color: var(--green); }
.score-label { color: var(--text2); font-size: 15px; margin-top: 4px; }
.score-badge { display: inline-block; font-size: 14px; padding: 6px 16px; border-radius: 20px; margin: 16px 0; }
.score-btns { display: flex; flex-direction: column; gap: 10px; margin-top: 20px; }
.score-btn { padding: 14px; border-radius: var(--radius-sm); border: none; font-size: 15px; font-weight: 600; cursor: pointer; }
</style>
</head>
<body>

<!-- HOME -->
<div id="screen-home" class="screen active">
  <div class="top-nav" style="background:var(--green);">
    <span class="nav-icon">⚡</span>
    <h1>StudyApp IEE</h1>
  </div>
  <div class="home-header">
    <h2>Hola, estudiante 👋</h2>
    <p>Ingeniería de Ejecución Eléctrica</p>
  </div>
  <div class="section-label">Mis ramos</div>
  <div class="ramo-card" onclick="openRamo('se')">
    <div class="ramo-icon" style="background:#E1F5EE;">⚡</div>
    <div>
      <h3>Sistemas de Media y Alta Tensión</h3>
      <p>Subestaciones · Esquemas de barras · RIC N°13</p>
    </div>
    <span class="ramo-arrow">›</span>
  </div>
  <div class="add-card" onclick="alert('Próximamente: agregar más ramos')">
    <div class="ramo-icon" style="background:var(--gray-l);font-size:20px;">+</div>
    <span>Agregar otro ramo</span>
  </div>
  <div class="section-label">Acceso rápido</div>
  <div class="ramo-card" onclick="openModule('fc-ric')">
    <div class="ramo-icon" style="background:#FAEEDA;">🃏</div>
    <div><h3>Flashcards RIC N°13</h3><p>Repaso rápido de datos clave</p></div>
    <span class="ramo-arrow">›</span>
  </div>
  <div class="ramo-card" onclick="openModule('exam-se')">
    <div class="ramo-icon" style="background:#E6F1FB;">📝</div>
    <div><h3>Examen de práctica</h3><p>Subestaciones + RIC N°13</p></div>
    <span class="ramo-arrow">›</span>
  </div>
</div>

<!-- RAMO SE -->
<div id="screen-ramo-se" class="screen">
  <div class="top-nav">
    <button class="back-btn" onclick="goBack()">‹</button>
    <h1>Media y Alta Tensión</h1>
  </div>
  <div class="ramo-hero">
    <h2>Sistemas de Media y Alta Tensión</h2>
    <p>Selecciona un módulo para estudiar</p>
  </div>
  <div class="module-grid">
    <div class="module-card green" onclick="openModule('res-se')">
      <div class="m-icon">📚</div>
      <h4>Subestaciones</h4>
      <p>Componentes, tipos y organización</p>
    </div>
    <div class="module-card blue" onclick="openModule('res-barras')">
      <div class="m-icon">🗂️</div>
      <h4>Esquemas de barras</h4>
      <p>Los 8 esquemas con ventajas y desventajas</p>
    </div>
    <div class="module-card amber" onclick="openModule('res-ric')">
      <div class="m-icon">📋</div>
      <h4>RIC N°13</h4>
      <p>Norma SEC: distancias, exigencias, protecciones</p>
    </div>
    <div class="module-card green" onclick="openModule('fc-ric')">
      <div class="m-icon">🃏</div>
      <h4>Flashcards</h4>
      <p>Datos clave RIC N°13</p>
    </div>
    <div class="module-card red" onclick="openModule('exam-se')">
      <div class="m-icon">📝</div>
      <h4>Examen</h4>
      <p>Practica con preguntas del certamen</p>
    </div>
    <div class="module-card blue" onclick="openModule('tabla-dist')">
      <div class="m-icon">📐</div>
      <h4>Tabla distancias</h4>
      <p>Tabla N°13.1 interactiva</p>
    </div>
  </div>
</div>

<!-- RESUMEN SUBESTACIONES -->
<div id="screen-res-se" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>Subestaciones Eléctricas</h1></div>
  <div class="content-wrap">
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>¿Qué es una subestación?</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p>Una <b>subestación eléctrica (S/E)</b> es una instalación que realiza transformaciones de tensión, frecuencia, número de fases o conexiones de dos o más circuitos. Su equipo principal es el <b>transformador</b>.</p>
        <div class="info-box info-green">El transformador modifica la tensión mediante inducción electromagnética manteniendo la potencia constante.</div>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Componentes principales</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p><b>Sistema AT/MT:</b> Barras, interruptores de potencia, seccionadores, pararrayos, transformadores de medida (TC/TT).</p>
        <p><b>Transformadores de potencia:</b> Cambian el nivel de tensión. Tienen devanado primario y secundario. Refrigeración por aceite dieléctrico o ventiladores.</p>
        <p><b>Sistema de protección:</b> Relés de protección, SCADA (monitoreo remoto), baterías CC.</p>
        <p><b>Puesta a tierra:</b> Disipa corrientes de falla. Electrodos + malla de tierra.</p>
        <div class="info-box info-blue"><b>SCADA:</b> Supervisory Control and Data Acquisition. Monitorea y opera la S/E de forma remota en tiempo real.</div>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Tipos de subestaciones</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p><b>Por función:</b></p>
        <div style="margin:8px 0"><span class="tag tag-g">Elevadora</span> Eleva tensión de MT a AT (66, 110, 220, 380 kV) para transporte</div>
        <div style="margin:8px 0"><span class="tag tag-b">Reductora</span> Reduce AT a MT (6-30 kV) para distribución</div>
        <div style="margin:8px 0"><span class="tag tag-a">Maniobra</span> Conecta circuitos sin transformar tensión</div>
        <p style="margin-top:12px"><b>Por aislamiento:</b></p>
        <div class="info-box info-green"><b>AIS</b> (Air Insulated): Aislada por aire. Más espacio, más económica.</div>
        <div class="info-box info-blue"><b>GIS</b> (Gas Insulated): Aislada con SF₆. Compacta, mayor mantenimiento. Desde los años 70.</div>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Centro de Transformación (CT)</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p>Es un tipo específico de S/E. Entrega tensión a usuarios finales: <b>380 V trifásico / 230 V monofásico</b>.</p>
        <table class="data-table">
          <tr><th>Tipo</th><th>Descripción</th></tr>
          <tr><td>De punta</td><td>Al final de una línea</td></tr>
          <tr><td>De paso</td><td>Punto medio de línea</td></tr>
          <tr><td>De anillo</td><td>Alimentado por dos extremos. Más confiable. Ciudades.</td></tr>
          <tr><td>Intemperie (CTI)</td><td>Sobre poste. Zonas rurales. Máx 160 kVA.</td></tr>
        </table>
        <div class="info-box info-amber"><b>¿Por qué alta tensión para transporte?</b> A mayor tensión → menor corriente → menores pérdidas por efecto Joule (P = I²·R).</div>
      </div>
    </div>
  </div>
</div>

<!-- RESUMEN ESQUEMAS DE BARRAS -->
<div id="screen-res-barras" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>Esquemas de Barras</h1></div>
  <div class="content-wrap" id="barras-content"></div>
</div>

<!-- RESUMEN RIC 13 -->
<div id="screen-res-ric" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>RIC N°13</h1></div>
  <div class="content-wrap">
    <div class="info-box info-green" style="margin-bottom:12px"><b>¿Qué es?</b> Pliego Técnico Normativo de la SEC. Regula subestaciones hasta 23.000 V en instalaciones de consumo en Chile.</div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Clasificación constructiva</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p><b>5.1.1</b> A la intemperie: aéreas o a nivel de piso</p>
        <p><b>5.1.2</b> Bajo techo: en interior de edificios o aisladas</p>
        <p><b>5.1.3</b> En bóvedas: subterráneas (techo a nivel de piso o sobresale máx. 0,80 m)</p>
        <p><b>5.1.4</b> Compactas: módulos independientes en caja metálica</p>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Exigencias generales</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <div class="info-box info-amber"><b>Instalador clase A</b> obligatorio para ejecutar el proyecto (punto 6.1.2)</div>
        <p>Debe existir un <b>esquema unilineal</b> visible cerca de los tableros con: tensiones nominales, clases de transformadores, circuitos, protecciones y características de puesta a tierra.</p>
        <div class="info-box info-blue">Aplica solo a altitudes <b>menores de 1.000 m s.n.m.</b></div>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Subestaciones a la intemperie</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <table class="data-table">
          <tr><th>Exigencia</th><th>Valor</th></tr>
          <tr><td>Altura mínima cierre</td><td><b>2,00 m</b> (2,50 m calle)</td></tr>
          <tr><td>Dist. horizontal cierre-equipo</td><td><b>≥ 1,50 m</b></td></tr>
          <tr><td>Tierra del cierre</td><td>Cada <b>15 m</b>, mín. 2 conexiones</td></tr>
          <tr><td>Base equipo nivel suelo</td><td>Concreto <b>≥ 0,25 m</b> espesor</td></tr>
          <tr><td>Gravilla en suelo</td><td><b>0,05 m</b> espesor, 1 m más allá del cierre</td></tr>
        </table>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Subestaciones en interior</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <table class="data-table">
          <tr><th>Exigencia</th><th>Valor</th></tr>
          <tr><td>Puerta de servicio</td><td><b>0,80 × 2,10 m</b>, abre hacia exterior</td></tr>
          <tr><td>Ventilación natural</td><td><b>20 cm²/kVA</b></td></tr>
          <tr><td>Ventilación forzada</td><td><b>20 renovaciones/hora</b></td></tr>
          <tr><td>Foso colector aceite</td><td>Aceite mayor trafo + <b>30%</b> del resto</td></tr>
        </table>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Edificios de uso general</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p>Solo aislante <b>tipo seco o líquido clase K</b> (T° ignición > 300°C)</p>
        <p>Muros cortafuego: <b>albañilería 0,20 m</b> o <b>concreto 0,10 m</b></p>
        <p>Trafo seco > 100 kVA → <b>sonda PT100</b></p>
        <p>Trafo aceite > 250 kVA → <b>relé Buchholz</b> o detector sobretemperatura</p>
        <p>Vía de escape hasta exterior: <b>&lt; 10 m</b></p>
        <div class="info-box info-amber">Muro separación entre trafos: <b>≥ 2,50 m</b></div>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Protecciones (Tabla N°13.3)</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <table class="data-table">
          <tr><th>Impedancia</th><th>Auto. primario</th><th>Fusible primario</th></tr>
          <tr><td>≤ 0,06</td><td>6 × In</td><td>3 × In</td></tr>
          <tr><td>> 0,06</td><td>4 × In</td><td>2 × In</td></tr>
        </table>
        <div class="info-box info-green"><b>Regla clave:</b> Fusible = mitad del automático siempre (6→3, 4→2)</div>
        <p>Reconectadores obligatorios si potencia en MT ≥ <b>500 kW</b></p>
      </div>
    </div>
    <div class="topic-card">
      <div class="topic-header" onclick="toggleTopic(this)"><h3>Puesta a tierra</h3><span class="chevron">▼</span></div>
      <div class="topic-body">
        <p><b>Protección:</b> Conecta partes metálicas no activas (carcasas, puertas, cercos, mufas).</p>
        <p><b>Servicio:</b> Se dimensiona con la máxima corriente de falla a tierra.</p>
        <div class="info-box info-amber">Falla <b>permanente</b> = despejada en más de <b>3 segundos</b></div>
      </div>
    </div>
  </div>
</div>

<!-- TABLA DISTANCIAS -->
<div id="screen-tabla-dist" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>Tabla N°13.1 — Distancias</h1></div>
  <div class="content-wrap">
    <div class="info-box info-blue" style="margin-bottom:16px">Distancias mínimas para conductores y barras desnudas energizadas (Tabla N°13.1 RIC N°13)</div>
    <table class="data-table">
      <tr><th>kV nominal</th><th>kV máx</th><th>Entre fases interior</th><th>F-T interior</th><th>Entre fases intemperie</th><th>F-T intemperie</th></tr>
      <tr><td>2,4</td><td>2,75</td><td>130 mm</td><td>100 mm</td><td>150 mm</td><td>100 mm</td></tr>
      <tr><td>3,3</td><td>3,6</td><td>150 mm</td><td>120 mm</td><td>180 mm</td><td>120 mm</td></tr>
      <tr><td>4,16</td><td>5</td><td>170 mm</td><td>130 mm</td><td>180 mm</td><td>120 mm</td></tr>
      <tr><td>6,6</td><td>7,2</td><td>200 mm</td><td>150 mm</td><td>200 mm</td><td>150 mm</td></tr>
      <tr><td>13,2</td><td>15</td><td>300 mm</td><td>200 mm</td><td>300 mm</td><td>200 mm</td></tr>
      <tr><td><b>23</b></td><td><b>25</b></td><td><b>400 mm</b></td><td><b>300 mm</b></td><td><b>500 mm</b></td><td><b>400 mm</b></td></tr>
    </table>
    <div class="info-box info-green" style="margin-top:16px"><b>Truco para recordar:</b> Desde 6,6 kV, las distancias entre fases interior suben de 100 en 100: 200 → 300 → 400 mm. Y la distancia F-T es siempre menor que entre fases.</div>
    <div class="info-box info-amber" style="margin-top:8px"><b>23 kV intemperie es el mayor:</b> 500 mm entre fases y 400 mm fase-tierra. El más exigente de la tabla.</div>
  </div>
</div>

<!-- FLASHCARDS RIC -->
<div id="screen-fc-ric" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>Flashcards RIC N°13</h1></div>
  <div class="fc-wrap" id="fc-content"></div>
</div>

<!-- EXAMEN -->
<div id="screen-exam-se" class="screen">
  <div class="top-nav"><button class="back-btn" onclick="goBack()">‹</button><h1>Examen de Práctica</h1></div>
  <div class="exam-wrap" id="exam-content"></div>
</div>

<!-- BOTTOM NAV -->
<nav class="bottom-nav">
  <button class="bnav-btn active" id="bnav-home" onclick="showScreen('home')"><span class="icon">🏠</span>Inicio</button>
  <button class="bnav-btn" id="bnav-study" onclick="openRamo('se')"><span class="icon">📚</span>Estudiar</button>
  <button class="bnav-btn" id="bnav-fc" onclick="openModule('fc-ric')"><span class="icon">🃏</span>Flashcards</button>
  <button class="bnav-btn" id="bnav-exam" onclick="openModule('exam-se')"><span class="icon">📝</span>Examen</button>
</nav>

<script>
// ── DATA ──────────────────────────────────────────────────────────
const BARRAS = [
  { n:"1. Barra Simple", costo:"Bajo", conf:"Baja", mant:"No", color:"red",
    desc:"La configuración más básica y económica. Una sola barra conecta todo. No apta para subestaciones de gran envergadura.",
    pros:["Instalación simple","Maniobras sencillas","Bajo costo"],
    cons:["Falla en barra o interruptor = toda la S/E cae","Mantenimiento requiere cortar servicio completo","Imposible ampliar sin interrumpir suministro"],
    clave:"Una falla en cualquier punto deja TODA la subestación sin servicio.",
    uso:"Subestaciones pequeñas o rurales de baja criticidad." },
  { n:"2. Barra Simple + Transferencia", costo:"Bajo-medio", conf:"Baja", mant:"Parcial", color:"amber",
    desc:"Agrega una barra de transferencia con interruptor propio. Permite aislar un interruptor para mantenimiento sin cortar el servicio de ese circuito.",
    pros:["Bajo costo","Permite mantenimiento de interruptores sin interrumpir el servicio"],
    cons:["Requiere interruptor de transferencia adicional","Falla en cualquier barra = toda la S/E cae"],
    clave:"Permite mantenimiento de interruptores individuales, pero falla de barra = toda la S/E cae.",
    uso:"Instalaciones pequeñas con necesidad de mantención sin cortes." },
  { n:"3. Barra Seccionada", costo:"Medio", conf:"Media", mant:"Parcial", color:"amber",
    desc:"Barra dividida por un interruptor acoplador central. Equivale a dos barras simples conectadas. Falla en una sección → solo esa parte pierde servicio.",
    pros:["Mayor continuidad de servicio","Falla en una sección no afecta la otra","Mayor flexibilidad en mantención"],
    cons:["No se puede transferir línea de una barra a otra","Mantención de un interruptor corta esa línea","Protecciones más complejas"],
    clave:"Falla en una sección → solo esa mitad cae. La otra sigue.",
    uso:"Instalaciones medianas que necesitan separar la carga en dos secciones." },
  { n:"4. Barra Seccionada + Transferencia", costo:"Medio-alto", conf:"Media-alta", mant:"Sí", color:"green",
    desc:"Combina barra seccionada con barra de transferencia. Mayor flexibilidad operacional.",
    pros:["Mantenimiento de interruptores sin cortar servicio","Falla en una barra: solo esa parte cae","Mayor continuidad"],
    cons:["Solo transfiere UN circuito a la vez","Más costoso","Protecciones más complejas"],
    clave:"Más flexible que la seccionada sola. Solo puede transferir UN circuito a la vez.",
    uso:"Subestaciones medianas con necesidad de flexibilidad operacional." },
  { n:"5. Doble Barra", costo:"Alto", conf:"Alta", mant:"Sí", color:"green",
    desc:"Dos barras conectadas por interruptor acoplador. Cada circuito puede conectarse a CUALQUIERA de las dos barras. Muy usado en S/E con muchos circuitos.",
    pros:["Cualquier barra puede aislarse sin interrumpir circuitos","Circuito puede cambiar de barra bajo carga","Gran flexibilidad"],
    cons:["Interruptor acoplador extra","Falla del acoplador = toda la S/E cae","Alta exposición a fallas de barra"],
    clave:"Falla del interruptor acoplador = toda la S/E fuera de servicio.",
    uso:"Subestaciones importantes con muchos circuitos y gran potencia." },
  { n:"6. Doble Barra + Transferencia", costo:"Alto", conf:"Alta", mant:"Sí", color:"green",
    desc:"Agrega barra de transferencia al esquema de doble barra. Permite aislar interruptores para mantenimiento además de cambiar circuitos de barra.",
    pros:["Máxima flexibilidad de la doble barra","Mantenimiento de interruptores sin cortar","Transferencia fácil entre barras"],
    cons:["Mayor costo y complejidad","Falla del acoplador puede dejar fuera toda la S/E"],
    clave:"Doble barra con capacidad de mantenimiento de interruptores sin interrupciones.",
    uso:"Subestaciones grandes con alta exigencia de flexibilidad." },
  { n:"7. Doble Barra + Doble Interruptor", costo:"Muy alto", conf:"Muy alta", mant:"Sí", color:"green",
    desc:"Cada circuito tiene DOS interruptores propios, uno para cada barra. Normalmente conectados a ambas barras simultáneamente. Muy alta confiabilidad.",
    pros:["Cada circuito tiene 2 interruptores exclusivos","Cualquier interruptor puede retirarse para mantención","Alta confiabilidad"],
    cons:["El más costoso de los esquemas convencionales","Si no conectado a ambas barras, falla puede cortar la mitad"],
    clave:"Máxima confiabilidad convencional. Cada circuito tiene su propio interruptor para cada barra.",
    uso:"Subestaciones de gran potencia donde la continuidad es crítica." },
  { n:"8. Interruptor y Medio ⭐", costo:"Alto", conf:"Muy alta", mant:"Sí", color:"green",
    desc:"EL MÁS USADO en alta tensión. 3 interruptores para 2 circuitos (1,5 por circuito). Todos normalmente cerrados. Combina seguridad de malla con flexibilidad de doble barra.",
    pros:["Alta confiabilidad","Falla de barra NO interrumpe ningún circuito","Mantenimiento siempre sin cortar servicio","Operación sencilla sin desconectadores","Cualquier interruptor puede retirarse para mantención"],
    cons:["Alto costo (1,5 interruptores por circuito)","Falla del interruptor central saca 2 circuitos","Protecciones más complejas"],
    clave:"FALLA DE BARRA = NO cae ningún circuito. Falla interruptor central = salen 2 circuitos.",
    uso:"Transmisión ≥ 220 kV, generación. Especialmente 500 kV o superior." }
];

const FLASHCARDS = [
  { q:"¿Cuál es la tensión máxima de aplicación del RIC N°13?", a:"23.000 V", e:"Se aplica a instalaciones de consumo con transformadores de hasta 23 kV." },
  { q:"¿Qué instalador debe ejecutar el proyecto de una subestación según el RIC N°13?", a:"Instalador clase A", e:"El más alto nivel de habilitación (punto 6.1.2)." },
  { q:"Distancia mínima ENTRE FASES en interior para 13,2 kV", a:"300 mm", e:"Tabla N°13.1. Desde 6,6 kV sube de 100 en 100: 200→300→400 mm." },
  { q:"Distancia mínima FASE A TIERRA en interior para 13,2 kV", a:"200 mm", e:"Tabla N°13.1. Siempre menor que la distancia entre fases." },
  { q:"Distancia mínima ENTRE FASES a la intemperie para 23 kV", a:"500 mm", e:"El mayor valor de la Tabla N°13.1. A la intemperie es más exigente que en interior." },
  { q:"Distancia mínima FASE A TIERRA a la intemperie para 23 kV", a:"400 mm", e:"Tabla N°13.1. El mayor valor fase-tierra de la tabla." },
  { q:"Altura mínima del cierre de protección en subestación a la intemperie", a:"2,00 m", e:"Si colinda con sitio público: 2,50 m + protección anti-escalamiento (punto 7.2.6)." },
  { q:"Distancia horizontal mínima del cierre al equipo eléctrico", a:"1,50 m", e:"Medida desde la proyección de cualquier punto del equipo (punto 7.2.6)." },
  { q:"¿Cada cuántos metros se exige una conexión a tierra en el cierre metálico?", a:"Cada 15 m", e:"Con un mínimo de 2 conexiones totales (punto 7.2.10)." },
  { q:"Dimensiones mínimas de la puerta de servicio en subestación interior", a:"0,80 × 2,10 m", e:"Debe abrir hacia el exterior y tener cerradura que abra desde dentro sin llave (punto 8.6)." },
  { q:"Ventilación natural: ¿cuántos cm² por kVA se requieren?", a:"20 cm² por kVA", e:"Para circulación natural de aire en recintos de subestación interior (punto 8.10)." },
  { q:"Ventilación forzada: ¿cuántas renovaciones de aire por hora?", a:"20 renovaciones/hora", e:"Mínimo 20 renovaciones del volumen total del recinto (punto 8.10)." },
  { q:"Capacidad mínima del foso colector para transformadores en aceite", a:"Aceite mayor trafo + 30% del resto", e:"Para contener derrames en caso de falla (punto 8.8)." },
  { q:"¿Qué aislante se permite en edificios de uso general?", a:"Tipo seco o líquido clase K (>300°C)", e:"IEC 61039. Temperatura de ignición superior a 300°C (punto 9.1)." },
  { q:"¿Qué protección exige el RIC para trafo en aceite >250 kVA en edificio?", a:"Relé Buchholz o detector sobretemperatura", e:"Buchholz detecta gases generados por fallas internas en el aceite (punto 9.8)." },
  { q:"Distancia máxima de la vía de escape en subestación dentro de edificio", a:"Menos de 10 m", e:"Desde el recinto hasta el exterior del edificio (punto 9.5)." },
  { q:"Protección primaria con FUSIBLE para trafo con impedancia ≤ 0,06", a:"Máximo 3 × In", e:"Tabla N°13.3. Fusible = mitad del automático (automático es 6 × In)." },
  { q:"Protección primaria con FUSIBLE para trafo con impedancia > 0,06", a:"Máximo 2 × In", e:"Tabla N°13.3. Fusible = mitad del automático (automático es 4 × In)." },
  { q:"¿A partir de qué potencia en MT se exigen reconectadores automáticos?", a:"500 kW o más", e:"Punto 13.6. Cuando los niveles de cortocircuito lo ameriten y potencia ≥ 500 kW." },
  { q:"¿Cuándo una falla se considera PERMANENTE según el RIC N°13?", a:"Si se despeja en más de 3 segundos", e:"Punto 14.1.7. Fallas de menos de 3 segundos se consideran transitorias." }
];

const EXAM_QS = [
  { q:"¿Cuál es el campo de aplicación del RIC N°13?", opts:["Subestaciones de hasta 66 kV","Instalaciones con transformadores hasta 23.000 V de consumo","Red de transmisión nacional","Subestaciones de generación"], ans:1, exp:"El RIC N°13 se aplica a instalaciones de consumo con transformadores que operan hasta 23.000 V." },
  { q:"¿Qué clase de instalador debe ejecutar el proyecto de una subestación?", opts:["Clase B","Clase C","Clase A","Cualquier instalador habilitado"], ans:2, exp:"Punto 6.1.2: instalador eléctrico autorizado clase A, la categoría más alta." },
  { q:"Distancia mínima entre fases en interior para 13,2 kV (Tabla N°13.1)", opts:["200 mm","150 mm","300 mm","400 mm"], ans:2, exp:"Tabla N°13.1: 13,2 kV interior → entre fases = 300 mm. Desde 6,6 kV sube de 100 en 100." },
  { q:"Distancia mínima entre fases a la intemperie para 23 kV (Tabla N°13.1)", opts:["300 mm","400 mm","500 mm","600 mm"], ans:2, exp:"Tabla N°13.1: 23 kV intemperie → entre fases = 500 mm. El valor más alto de la tabla." },
  { q:"Altura mínima del cierre de protección en S/E a la intemperie", opts:["1,50 m","1,80 m","2,00 m","2,50 m"], ans:2, exp:"Punto 7.2.6: mínimo 2,00 m. Si colinda con sitio público: 2,50 m." },
  { q:"¿Cada cuántos metros se exige una conexión a tierra en el cierre metálico?", opts:["5 m","10 m","15 m","20 m"], ans:2, exp:"Punto 7.2.10: una conexión a tierra por cada 15 m de perímetro, mínimo 2 conexiones." },
  { q:"Dimensiones mínimas de la puerta de servicio en subestación interior", opts:["0,60 × 1,80 m","0,70 × 2,00 m","0,80 × 2,10 m","1,00 × 2,20 m"], ans:2, exp:"Punto 8.6: mínimo 0,80 × 2,10 m, abre hacia el exterior." },
  { q:"Ventilación natural: superficie libre requerida por kVA", opts:["10 cm²","15 cm²","20 cm²","25 cm²"], ans:2, exp:"Punto 8.10: 20 cm² de superficie libre por cada kVA de potencia." },
  { q:"Protección primaria con fusible para impedancia ≤ 0,06 (Tabla N°13.3)", opts:["2 × In","4 × In","3 × In","6 × In"], ans:2, exp:"Tabla N°13.3: impedancia ≤ 0,06 → fusible primario máximo 3 × In (la mitad del automático que es 6 × In)." },
  { q:"¿Cuándo se considera falla permanente según el RIC N°13?", opts:["Más de 1 segundo","Más de 2 segundos","Más de 3 segundos","Más de 5 segundos"], ans:2, exp:"Punto 14.1.7: falla permanente = despejada en tiempo superior a 3 segundos." },
  { q:"El esquema de 'interruptor y medio' tiene:", opts:["1 interruptor por circuito","2 interruptores por circuito","1,5 interruptores por circuito","3 interruptores por circuito"], ans:2, exp:"3 interruptores para 2 circuitos = 1,5 por circuito. De ahí el nombre." },
  { q:"¿En qué esquema de barras falla del interruptor acoplador deja toda la S/E sin servicio?", opts:["Barra simple","Barra seccionada","Doble barra","Interruptor y medio"], ans:2, exp:"En la doble barra, si falla el interruptor seccionador-acoplador, toda la subestación queda fuera de servicio." },
  { q:"¿Qué esquema de barras es el más utilizado en subestaciones de transmisión ≥ 220 kV?", opts:["Barra simple","Doble barra","Barra seccionada","Interruptor y medio"], ans:3, exp:"El interruptor y medio es el más usado actualmente en alta tensión por su alta confiabilidad. Especialmente en 500 kV." },
  { q:"¿Qué protección exige el RIC para trafo en aceite >250 kVA instalado en edificio?", opts:["Extintores automáticos","Relé Buchholz o detector de sobretemperatura","Sonda PT100","Interruptor diferencial"], ans:1, exp:"Punto 9.8: transformadores en aceite >250 kVA en edificios de uso general requieren Buchholz o detector de sobretemperatura." },
  { q:"¿A partir de qué potencia en MT son obligatorios los reconectadores?", opts:["250 kW","500 kW","1.000 kW","100 kW"], ans:1, exp:"Punto 13.6: se exige reconectadores o interruptores automáticos cuando la potencia en MT es ≥ 500 kW." }
];

// ── NAVIGATION ────────────────────────────────────────────────────
let screenStack = ['home'];
function showScreen(id) {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById('screen-' + id).classList.add('active');
  document.querySelectorAll('.bnav-btn').forEach(b => b.classList.remove('active'));
  const map = { home:'bnav-home', 'ramo-se':'bnav-study', 'fc-ric':'bnav-fc', 'exam-se':'bnav-exam' };
  if (map[id]) document.getElementById(map[id]).classList.add('active');
  window.scrollTo(0, 0);
}
function openRamo(r) { screenStack.push('ramo-' + r); showScreen('ramo-' + r); }
function openModule(m) {
  screenStack.push(m);
  if (m === 'res-barras') buildBarrasContent();
  if (m === 'fc-ric') buildFlashcards();
  if (m === 'exam-se') buildExam();
  showScreen(m);
}
function goBack() {
  screenStack.pop();
  const prev = screenStack[screenStack.length - 1] || 'home';
  showScreen(prev);
}

// ── TOPICS ───────────────────────────────────────────────────────
function toggleTopic(header) {
  header.classList.toggle('open');
  const body = header.nextElementSibling;
  body.classList.toggle('show');
}

// ── BARRAS ───────────────────────────────────────────────────────
function buildBarrasContent() {
  const wrap = document.getElementById('barras-content');
  if (wrap.children.length > 0) return;
  const colorMap = { red:'#FCEBEB', amber:'#FAEEDA', green:'#E1F5EE' };
  const textMap = { red:'#A32D2D', amber:'#854F0B', green:'#0F6E56' };
  BARRAS.forEach(b => {
    const card = document.createElement('div');
    card.className = 'topic-card';
    card.innerHTML = `
      <div class="topic-header" onclick="toggleTopic(this)">
        <h3>${b.n}</h3><span class="chevron">▼</span>
      </div>
      <div class="topic-body">
        <div style="display:flex;gap:6px;flex-wrap:wrap;margin-bottom:10px">
          <span class="tag" style="background:${b.color==='green'?'#E1F5EE':b.color==='amber'?'#FAEEDA':'#FCEBEB'};color:${b.color==='green'?'#0F6E56':b.color==='amber'?'#854F0B':'#A32D2D'}">Costo: ${b.costo}</span>
          <span class="tag" style="background:${b.color==='green'?'#E1F5EE':'#FCEBEB'};color:${b.color==='green'?'#0F6E56':'#A32D2D'}">Confiabilidad: ${b.conf}</span>
          <span class="tag" style="background:${b.mant==='Sí'?'#E1F5EE':'#FCEBEB'};color:${b.mant==='Sí'?'#0F6E56':'#A32D2D'}">Mant. sin corte: ${b.mant}</span>
        </div>
        <p>${b.desc}</p>
        <div style="margin-top:8px"><b style="font-size:13px;color:#0F6E56">✓ Ventajas</b>
          ${b.pros.map(p=>`<div style="font-size:13px;padding:2px 0 2px 12px;color:#0F6E56">+ ${p}</div>`).join('')}
        </div>
        <div style="margin-top:8px"><b style="font-size:13px;color:#A32D2D">✗ Desventajas</b>
          ${b.cons.map(c=>`<div style="font-size:13px;padding:2px 0 2px 12px;color:#A32D2D">- ${c}</div>`).join('')}
        </div>
        <div class="info-box info-amber" style="margin-top:10px"><b>Dato clave:</b> ${b.clave}</div>
        <div class="info-box info-blue" style="margin-top:6px"><b>Uso típico:</b> ${b.uso}</div>
      </div>`;
    wrap.appendChild(card);
  });
}

// ── FLASHCARDS ───────────────────────────────────────────────────
let fcIdx = 0, fcFlipped = false, fcCorrect = 0;
const fcOrder = () => [...Array(FLASHCARDS.length).keys()].sort(() => Math.random() - 0.5);
let fcDeck = [];

function buildFlashcards() {
  fcIdx = 0; fcFlipped = false; fcCorrect = 0;
  fcDeck = fcOrder();
  renderFC();
}
function renderFC() {
  const wrap = document.getElementById('fc-content');
  if (fcIdx >= fcDeck.length) {
    wrap.innerHTML = `<div class="fc-result">
      <div class="big">${fcCorrect}/${FLASHCARDS.length}</div>
      <p>¡Completaste todas las flashcards!</p>
      <button onclick="buildFlashcards()">↩ Repetir</button>
    </div>`;
    return;
  }
  const card = FLASHCARDS[fcDeck[fcIdx]];
  const pct = Math.round((fcIdx / FLASHCARDS.length) * 100);
  wrap.innerHTML = `
    <div class="fc-progress">
      <div class="fc-bar"><div class="fc-fill" style="width:${pct}%"></div></div>
      <span class="fc-count">${fcIdx + 1} / ${FLASHCARDS.length}</span>
    </div>
    <div class="card-scene" onclick="flipFC()">
      <div class="card-3d" id="card3d">
        <div class="card-face card-front">
          <div class="label">Pregunta — toca para respuesta</div>
          <div class="question">${card.q}</div>
        </div>
        <div class="card-face card-back">
          <div class="answer">${card.a}</div>
          <div class="explain">${card.e}</div>
        </div>
      </div>
    </div>
    <p class="tap-hint" id="fc-hint">Toca la tarjeta para ver la respuesta</p>
    <div class="fc-btns" id="fc-btns" style="display:none">
      <button class="fc-btn fc-btn-no" onclick="fcAnswer(false)">No lo sabía</button>
      <button class="fc-btn fc-btn-yes" onclick="fcAnswer(true)">Lo sabía ✓</button>
    </div>`;
  fcFlipped = false;
}
function flipFC() {
  if (fcFlipped) return;
  fcFlipped = true;
  document.getElementById('card3d').classList.add('flipped');
  document.getElementById('fc-hint').textContent = '¿Lo sabías?';
  document.getElementById('fc-btns').style.display = 'flex';
}
function fcAnswer(knew) {
  if (knew) fcCorrect++;
  fcIdx++;
  renderFC();
}

// ── EXAM ─────────────────────────────────────────────────────────
let examIdx = 0, examScore = 0, examAnswered = false;
let examOrder = [];

function buildExam() {
  examIdx = 0; examScore = 0; examAnswered = false;
  examOrder = [...Array(EXAM_QS.length).keys()].sort(() => Math.random() - 0.5);
  renderExam();
}
function renderExam() {
  const wrap = document.getElementById('exam-content');
  if (examIdx >= examOrder.length) {
    const pct = Math.round((examScore / EXAM_QS.length) * 100);
    const badge = pct >= 90 ? ['¡Excelente!','#E1F5EE','#0F6E56'] : pct >= 70 ? ['Buen resultado','#FAEEDA','#854F0B'] : ['Necesitas repasar','#FCEBEB','#A32D2D'];
    wrap.innerHTML = `<div class="score-screen">
      <div class="score-big">${examScore}/${EXAM_QS.length}</div>
      <div class="score-label">${pct}% correcto</div>
      <div class="score-badge" style="background:${badge[1]};color:${badge[2]}">${badge[0]}</div>
      <div class="score-btns">
        <button class="score-btn" style="background:var(--green);color:white" onclick="buildExam()">↩ Nuevo examen</button>
        <button class="score-btn" style="background:var(--blue-l);color:var(--blue)" onclick="openModule('fc-ric')">Repasar flashcards</button>
      </div>
    </div>`;
    return;
  }
  const q = EXAM_QS[examOrder[examIdx]];
  const L = ['A','B','C','D'];
  wrap.innerHTML = `
    <div class="exam-q">
      <div class="q-num">Pregunta ${examIdx + 1} de ${EXAM_QS.length}</div>
      <div class="q-text">${q.q}</div>
      ${q.opts.map((o,i) => `<button class="opt-btn" id="opt${i}" onclick="pickExam(${i})"><span class="opt-l">${L[i]}.</span>${o}</button>`).join('')}
      <div id="exam-fb"></div>
    </div>`;
  examAnswered = false;
}
function pickExam(idx) {
  if (examAnswered) return;
  examAnswered = true;
  const q = EXAM_QS[examOrder[examIdx]];
  q.opts.forEach((_,i) => {
    const el = document.getElementById('opt' + i);
    if (i === q.ans) el.className = 'opt-btn correct';
    else if (i === idx) el.className = 'opt-btn wrong';
    else el.className = 'opt-btn disabled';
  });
  const ok = idx === q.ans;
  if (ok) examScore++;
  const wrap = document.getElementById('exam-content');
  document.getElementById('exam-fb').innerHTML = `
    <div class="opt-fb" style="background:${ok?'var(--green-l)':'var(--red-l)'};color:${ok?'var(--green-d)':'var(--red)'}">
      ${ok ? '✓ Correcto — ' : '✗ Incorrecto — '}${q.exp}
    </div>
    <button class="exam-next" onclick="nextExam()">${examIdx + 1 < EXAM_QS.length ? 'Siguiente →' : 'Ver resultado'}</button>`;
}
function nextExam() { examIdx++; renderExam(); }
</script>
</body>
</html>
