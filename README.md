<!DOCTYPE html>
<html>
<head>
  <title>Malla Académica – Gestión de la Hospitalidad</title>
  <style>
    body { font-family: sans-serif; padding: 20px; background: #fffaf0; }
    .trimestre { background: #ffdab9; border: 2px solid #cd853f; padding: 10px; margin: 10px 0; cursor: pointer; font-weight: bold; }
    .detalle { display: none; background: #fef8e4; padding: 10px; margin-top: 5px; border-left: 4px solid #cd853f; }
    .asignatura { margin-bottom: 8px; }
  </style>
</head>
<body>
  <h1>📘 Malla Académica – Gestión de la Hospitalidad</h1>
    <!-- Trimestres 1 al 15 -->
  <div class="trimestre" onclick="toggleDetalle('tri1')">1️⃣ Trimestre 1</div>
  <div class="detalle" id="tri1">
    <div class="asignatura"><strong>Introducción a la hospitalidad</strong></div>
    <div class="asignatura"><strong>Contabilidad I</strong></div>
    <div class="asignatura"><strong>Expresión oral y escrita</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri2')">2️⃣ Trimestre 2</div>
  <div class="detalle" id="tri2">
    <div class="asignatura"><strong>Gestión hotelera</strong></div>
    <div class="asignatura"><strong>Contabilidad II</strong></div>
    <div class="asignatura"><strong>Inglés técnico I</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri3')">3️⃣ Trimestre 3</div>
  <div class="detalle" id="tri3">
    <div class="asignatura"><strong>Gestión de alimentos y bebidas</strong></div>
    <div class="asignatura"><strong>Contabilidad hotelera</strong></div>
    <div class="asignatura"><strong>Turismo responsable</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri4')">4️⃣ Trimestre 4</div>
  <div class="detalle" id="tri4">
    <div class="asignatura"><strong>Legislación turística</strong></div>
    <div class="asignatura"><strong>Gestión de reservas</strong></div>
    <div class="asignatura"><strong>Psicología del cliente</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri5')">5️⃣ Trimestre 5</div>
  <div class="detalle" id="tri5">
    <div class="asignatura"><strong>Marketing turístico</strong></div>
    <div class="asignatura"><strong>Contabilidad gerencial</strong></div>
    <div class="asignatura"><strong>Operaciones de recepción</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri6')">6️⃣ Trimestre 6</div>
  <div class="detalle" id="tri6">
    <div class="asignatura"><strong>Gestión financiera</strong></div>
    <div class="asignatura"><strong>Organización de eventos</strong></div>
    <div class="asignatura"><strong>Gestión de lavandería</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri7')">7️⃣ Trimestre 7</div>
  <div class="detalle" id="tri7">
    <div class="asignatura"><strong>Sistema de calidad hotelera</strong></div>
    <div class="asignatura"><strong>Costos y presupuestos</strong></div>
    <div class="asignatura"><strong>Gestión del talento humano</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri8')">8️⃣ Trimestre 8</div>
  <div class="detalle" id="tri8">
    <div class="asignatura"><strong>Estadística aplicada</strong></div>
    <div class="asignatura"><strong>Gestión ambiental</strong></div>
    <div class="asignatura"><strong>Diseño de proyectos turísticos</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri9')">9️⃣ Trimestre 9</div>
  <div class="detalle" id="tri9">
    <div class="asignatura"><strong>Sistemas informáticos hoteleros</strong></div>
    <div class="asignatura"><strong>Auditoría interna</strong></div>
    <div class="asignatura"><strong>Seguridad y riesgos</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri10')">🔟 Trimestre 10</div>
  <div class="detalle" id="tri10">
    <div class="asignatura"><strong>Administración estratégica</strong></div>
    <div class="asignatura"><strong>Gestión de mantenimiento hotelero</strong></div>
    <div class="asignatura"><strong>Gestión de conflictos</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri11')">1️⃣1️⃣ Trimestre 11</div>
  <div class="detalle" id="tri11">
    <div class="asignatura"><strong>Gestión de spa y bienestar</strong></div>
    <div class="asignatura"><strong>Contabilidad fiscal</strong></div>
    <div class="asignatura"><strong>Dirección de operaciones</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri12')">1️⃣2️⃣ Trimestre 12</div>
  <div class="detalle" id="tri12">
    <div class="asignatura"><strong>Gestión de restaurantes</strong></div>
    <div class="asignatura"><strong>Inglés técnico II</strong></div>
    <div class="asignatura"><strong>Gestión de calidad alimentaria</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri13')">1️⃣3️⃣ Trimestre 13</div>
  <div class="detalle" id="tri13">
    <div class="asignatura"><strong>Consultoría de hospitalidad</strong></div>
    <div class="asignatura"><strong>Gestión de patrimonio turístico</strong></div>
    <div class="asignatura"><strong>Finanzas corporativas</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri14')">1️⃣4️⃣ Trimestre 14</div>
  <div class="detalle" id="tri14">
    <div class="asignatura"><strong>Práctica profesional supervisada</strong></div>
    <div class="asignatura"><strong>Evaluación de proyectos</strong></div>
    <div class="asignatura"><strong>Seminario de investigación</strong></div>
  </div>

  <div class="trimestre" onclick="toggleDetalle('tri15')">1️⃣5️⃣ Trimestre 15</div>
  <div class="detalle" id="tri15">
    <div class="asignatura"><strong>Trabajo de grado</strong></div>
    <div class="asignatura"><strong>Defensa de proyecto final</strong></div>
  </div>
    <script>
    function toggleDetalle(id) {
      let elemento = document.getElementById(id);
      elemento.style.display = (elemento.style.display === 'none' || elemento.style.display === '') ? 'block' : 'none';
    }
  </script>
</body>
</html>
