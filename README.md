<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Expositions Paris</title>
<link rel="stylesheet" href="https://cdn.datatables.net/1.13.6/css/jquery.dataTables.min.css">
<style>
body { font-family: Arial, sans-serif; padding: 20px; }
h1 { margin-bottom: 20px; }
</style>
</head>
<body>

<h1>Expositions en cours à Paris – 6 septembre 2025</h1>

<table id="exposTable" class="display">
    <thead>
        <tr>
            <th>Musée</th>
            <th>Exposition</th>
            <th>Dates</th>
            <th>Lien</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Musée d'Orsay</td>
            <td>Destination Musée d'Orsay</td>
            <td>jusqu’au 28 sept. 2025</td>
            <td><a href="https://www.musee-orsay.fr/fr/agenda/expositions" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Quai Branly</td>
            <td>Tarō Okamoto</td>
            <td>jusqu’au 7 sept. 2025</td>
            <td><a href="https://www.quaibranly.fr/fr/agenda/expositions/" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Palais de Tokyo</td>
            <td>Vivian Suter – Disco</td>
            <td>jusqu’au 7 sept. 2025</td>
            <td><a href="https://www.palaisdetokyo.com/fr" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Marmottan Monet</td>
            <td>Morisot / PétrovitchSOLEIL</td>
            <td>jusqu’au 14 sept. 2025</td>
            <td><a href="https://www.marmottan.fr/expositions/" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Musée Maillol</td>
            <td>Robert Doisneau – Instants Donnés</td>
            <td>en cours</td>
            <td><a href="https://museemaillol.com/expositions/" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Musée Guimet</td>
            <td>Haïkus d’argent – Michael Kenna</td>
            <td>jusqu’au 29 sept. 2025</td>
            <td><a href="https://www.guimet.fr/expositions/" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Musée de la Chasse et de la Nature</td>
            <td>Courbet inédit (1864)</td>
            <td>jusqu’au 31 déc. 2025</td>
            <td><a href="https://www.chassenature.org/" target="_blank">Lien</a></td>
        </tr>
        <tr>
            <td>Fondation EDF</td>
            <td>Ce que l’horizon promet</td>
            <td>jusqu’au 28 sept. 2025</td>
            <td><a href="https://fondation.edf.com/nos-expositions/" target="_blank">Lien</a></td>
        </tr>
    </tbody>
</table>

<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="https://cdn.datatables.net/1.13.6/js/jquery.dataTables.min.js"></script>
<script>
$(document).ready(function() {
    $('#exposTable').DataTable({
        "paging": false,
        "info": false,
        "language": {
            "search": "Filtrer / rechercher :",
            "zeroRecords": "Aucune exposition trouvée",
        }
    });
});
</script>

</body>
</html>
