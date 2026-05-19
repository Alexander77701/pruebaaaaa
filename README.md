<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>CECP</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #f4f6f9;
}

.header {
    background: linear-gradient(to right, #ffffff 40%, #2f5d8a 60%);
    padding: 15px 30px;
    display: flex;
    align-items: center;
}

.logo {
    width: 90px;
    height: 90px;
    background: url('logo.png') no-repeat center;
    background-size: contain;
    margin-right: 20px;
}

.title {
    font-size: 26px;
    font-weight: bold;
    color: #000;
}

.menu {
    display: flex;
    justify-content: center;
    gap: 40px;
    margin-top: 20px;
}

.menu div {
    background: #e0e0e0;
    padding: 10px 25px;
    font-weight: bold;
    border-radius: 5px;
}

.container {
    display: flex;
    justify-content: center;
    margin-top: 40px;
    gap: 50px;
}

.box {
    width: 550px;
    background: transparent;
    padding: 10px;
    color: #333;
}

.highlight {
    margin-top: 20px;
    font-weight: bold;
}

.buttons {
    margin-top: 30px;
}

.btn {
    background: linear-gradient(135deg, #3aa6a6, #1f7a7a);
    color: white;
    border: none;
    padding: 14px 30px;
    border-radius: 12px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 5px 10px rgba(0,0,0,0.2);
}

.btn:hover {
    transform: translateY(-3px) scale(1.03);
    box-shadow: 0 8px 15px rgba(0,0,0,0.3);
}

.btn:active {
    transform: scale(0.97);
}

.footer {
    margin-top: 60px;
    background: #dcdcdc;
    padding: 15px;
    display: flex;
    justify-content: space-around;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="header">
    <div class="logo"></div>
    <div class="title">Corporación Especializada en Consultas Psicológicas</div>
</div>

<div class="menu">
    <div>VISIÓN</div>
    <div>MISIÓN</div>
    <div>OBJETIVO</div>
</div>

<div class="container">

    <div class="box">
        <h2>Nosotros</h2>

        Somos una empresa dedicada al bienestar de nuestros usuarios.
        En <strong>CECP</strong> estamos comprometidos por tu salud mental, ofreciendo
        planes accesibles para cada situación económica.

        Nuestro objetivo es brindarte un servicio de calidad, humano y profesional,
        acompañándote en cada paso de tu proceso.

        Queremos darte la bienvenida y que formes parte de las muchas personas
        que ya han confiado en nosotros.

        <div class="highlight">
            TE ESPERAMOS CON LOS BRAZOS ABIERTOS<br>
            Y LA MENTE AÚN MÁS
        </div>

        <div class="buttons">
            <button class="btn">AGENDAR CITA</button>
            <button class="btn">CONTÁCTANOS</button>
            <button class="btn">PLANES</button>
        </div>

    </div>

</div>

<div class="footer">
    <div>ACERCA DE</div>
    <div>TÉRMINOS DE USO</div>
    <div>SOPORTE</div>
    <div>CECP © 2026</div>
</div>

</body>
</html>
