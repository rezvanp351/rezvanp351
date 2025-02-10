<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Design Tools Icons</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="d-flex flex-wrap justify-content-center align-items-center mt-4">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" alt="Adobe Photoshop" data-bs-toggle="tooltip" title="Adobe Photoshop" style="width: 50px; margin: 5px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" alt="Adobe Illustrator" data-bs-toggle="tooltip" title="Adobe Illustrator" style="width: 50px; margin: 5px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/xd/xd-plain.svg" alt="Adobe XD" data-bs-toggle="tooltip" title="Adobe XD" style="width: 50px; margin: 5px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma" data-bs-toggle="tooltip" title="Figma" style="width: 50px; margin: 5px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sketch/sketch-original.svg" alt="Sketch" data-bs-toggle="tooltip" title="Sketch" style="width: 50px; margin: 5px;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/canva.svg" alt="Canva" data-bs-toggle="tooltip" title="Canva" style="width: 50px; margin: 5px; color: #00C4CC;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/gimp.svg" alt="GIMP" data-bs-toggle="tooltip" title="GIMP" style="width: 50px; margin: 5px; color: #5C5543;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/coreldraw.svg" alt="CorelDRAW" data-bs-toggle="tooltip" title="CorelDRAW" style="width: 50px; margin: 5px; color: #47A61E;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/affinitydesigner.svg" alt="Affinity Designer" data-bs-toggle="tooltip" title="Affinity Designer" style="width: 50px; margin: 5px; color: #1B72BE;">
</div>

<script>
    document.addEventListener("DOMContentLoaded", function () {
        var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'));
        var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
            return new bootstrap.Tooltip(tooltipTriggerEl);
        });
    });
</script>

</body>
</html>
