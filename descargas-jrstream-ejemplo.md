<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descargar JRStream - Versión de ejemplo</title>
    <meta name="description" content="Descarga la app de ejemplo JRStream para Android y Smart TV. Instrucciones de instalación y checksum SHA256 disponible.">
    <meta property="og:title" content="JRStream - Descargas" />
    <meta property="og:description" content="Descarga la app de ejemplo JRStream para Android y Smart TV. Sigue las instrucciones para instalar el APK de forma segura." />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://ejemplo.jrstreaming.local/descargas" />
    <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=JRStream+Ejemplo" />

    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-900 text-white font-sans flex flex-col min-h-screen justify-between">

    <header class="p-6 text-center">
        <h1 class="text-3xl font-extrabold tracking-wider text-cyan-400">
            <i class="fa-solid fa-play-circle mr-2"></i>JRStream (Ejemplo)
        </h1>
        <p class="text-gray-400 text-sm mt-1">Entretenimiento y pruebas — versión de demostración</p>
    </header>

    <main class="max-w-md mx-auto px-4 py-8 text-center flex-grow flex flex-col justify-center items-center">
        
        <div class="w-32 h-32 bg-cyan-500 rounded-3xl flex items-center justify-center shadow-lg shadow-cyan-500/30 mb-6">
            <i class="fa-solid fa-tv text-6xl text-white"></i>
        </div>

        <h2 class="text-2xl font-bold mb-2">Descarga la App Oficial (Ejemplo)</h2>
        <p class="text-gray-400 mb-8 text-balance">
            Prueba la app de ejemplo para Android o instálala en tu Smart TV compatible. Archivo firmado y verificado.
        </p>

        <div class="w-full space-y-4">
            
            <a href="/downloads/jrstream-ejemplo.apk" download class="block w-full bg-cyan-500 hover:bg-cyan-600 text-white font-bold py-4 px-6 rounded-xl transition duration-300 transform hover:scale-105 shadow-md">
                <i class="fa-solid fa-download mr-2"></i> Descarga Directa (APK)
            </a>

            <a href="https://example.com/alternativo/jrstream-ejemplo.apk" target="_blank" rel="noopener noreferrer" class="block w-full bg-slate-800 hover:bg-slate-700 text-cyan-400 border border-cyan-500/30 font-bold py-4 px-6 rounded-xl transition duration-300">
                <i class="fa-brands fa-android mr-2"></i> Servidor Alternativo
            </a>

        </div>

        <div class="mt-6 w-full text-left">
            <div class="bg-slate-800/50 p-4 rounded-xl border border-slate-700">
                <h3 class="text-sm font-semibold text-cyan-400 mb-1"><i class="fa-solid fa-circle-info mr-1"></i> ¿Cómo instalar?</h3>
                <p class="text-xs text-gray-400 leading-relaxed">
                    1) Descarga el APK. 2) En Android ve a Ajustes → Seguridad y activa "Orígenes desconocidos" o permite la instalación desde la app que uses para descargar. 3) Abre el archivo y sigue las instrucciones.
                </p>
            </div>

            <div class="mt-4 bg-slate-800/50 p-4 rounded-xl border border-slate-700">
                <h3 class="text-sm font-semibold text-cyan-400 mb-1"><i class="fa-solid fa-shield-halved mr-1"></i> Verificación (SHA256)</h3>
                <p class="text-xs text-gray-400 leading-relaxed break-all">
                    SHA256: <code id="sha">f2c3a4b5c6d7e8f9a0b1c2d3e4f5678901234567890abcdef1234567890abcd</code>
                </p>
                <p class="text-xs text-gray-400 mt-2">Compara este hash con el de tu archivo para verificar integridad.</p>
            </div>
        </div>

    </main>

    <footer class="p-6 text-center text-xs text-gray-500 border-t border-slate-800">
        &copy; 2026 JRStream (Ejemplo). Recursos de demostración.
    </footer>

</body>
</html>
