
# Maxcn.github.io

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UbiSocial</title>
    <link rel="stylesheet" href="ho.css">

</head>
<body>
    <p id="paragraph">Bienvenue sur UbiSocial votre gestionnaire de réseau en ligne !</p>
    <form method="POST" action="reseaux_sociaux.php">

        <fieldset>
            <legend>Identification Ubisocial :</legend>
            <label for="Votre e-mail">Email :</label>
            <input type="email" name="email" id="email" />
            <label for="Votre mot de passe">Mot de passe :</label>
            <input type="password" name="password" id="password" />
        </fieldset>

        <fieldset>
            <legend>Votre message :</legend>
    
            <legend>Vous voulez poster sur :</legend>
            <p></p>
            <label for="id1">Facebook :</label>
            <input type="checkbox" name="facebook" id="id1" value="valeur1"/></br>
            <label for="id2">Twitter :</label>
            <input type="checkbox" name="twitter" id="id2" value="valeur2"/></br>
            <label for="id3">Whatsapp :</label>
            <input type="checkbox" name="whatsapp" id="id3" value="valeur3" /></br>
            <p></p>
            <legend>Votre humeur :</legend>
            <select name="-Choississez-">
                <option value="valeur4">Joyeux</option></br>
                <option value="valeur5">Triste</option></br>
                <option value="valeur6">En colere</option>
            </select>
            <p></p>
            <legend>Exprimez vous !:</legend>
            <textarea name="texte" id="texte1" cols="300" rows="10"></textarea>

        </fieldset>

        <fieldset>
            <legend>Vos réseaux sociaux :</legend>
            <label for="Votre téléphone">No.Mobile Whatsapp :</label>
            <input type="telephone" name="tel" id="idtel" />
            <label for="pagefacebook">Page facebook :</label>
            <input type="url" name="urlfacebook" id="idpage" />
            <label for="cptTwitter">Compte Twitter :</label>
            <input type="texte" name="texte1" id="idtexte" />
            
        </fieldset>

        <fieldset>
            <legend>Vous voulez mettre votre commentaire en :</legend>
            <label for="id7">Gras</label>
            <input type="checkbox" name="gras" id="id7" value="valeur7"/></br>
            <label for="id8">italiques</label>
            <input type="checkbox" name="twitter" id="id8" value="valeur8"/>
        </fieldset>  
    </form>
    <p></p>
    <input type="submit" value="Envoyer" />
    <input type="reset" value="Recommencer" />
    

</body>
</html>
