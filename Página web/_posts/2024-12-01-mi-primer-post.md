---
layout: default
title: "¿Usamos solo el 10% del cerebro?"
author: "Dr. Lucas"
---

<!-- ENCABEZADO -->
<header class="mb-10 text-center">
    <h1 class="text-3xl md:text-5xl font-black text-gray-900 leading-tight mb-6">{{ page.title }}</h1>
    <div class="text-sm text-gray-500 ui-font">Por {{ page.author }}</div>
</header>

<!-- CUERPO DEL ARTICULO -->
<article class="text-lg md:text-xl leading-relaxed text-gray-700 space-y-6">
    <p>
        Es un mito común. 
        <!-- Ejemplo de Fuente -->
        <span class="source-wrapper" data-source-id="src-1">
            La evidencia demuestra que la mayor parte de la corteza cerebral está activa.
        </span>
    </p>

    <p>
        <!-- Ejemplo de Glosario -->
        Las <span class="term" data-def="Células del sistema nervioso.">neuronas</span> no funcionan solas.
    </p>
</article>

<hr class="my-12 border-gray-200">

<!-- BIBLIOGRAFÍA -->
<section class="bg-white rounded-xl border border-gray-200 p-6 shadow-sm ui-font text-sm">
    <h3 class="font-bold text-gray-900 mb-4">Referencias</h3>
    <ul>
        <li id="ref-src-1">[1] Drubach, D. (2000). The Brain Explained.</li>
    </ul>
</section>

<!-- DEFINICIÓN DE FUENTES (Esto es invisible pero necesario para que funcione el botón de fuentes) -->
<script>
    window.postSources = {
        'src-1': 'Estudio de Drubach (2000) sobre metabolismo cerebral.',
        'src-2': 'Otro paper científico.'
    };
</script>