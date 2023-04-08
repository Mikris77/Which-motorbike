# Which-motorbike
The best way to find the motorbike for your use !
<!DOCTYPE html>
<html>
<head>
  <title>Motos Sportives</title>
  <!-- Ajoutez ici les balises meta, les liens CSS et autres éléments d'en-tête nécessaires -->
</head>
<body>
  <h1>Motos Sportives</h1>
  <p>Voici les dernières motos sportives de chaque marque :</p>
  <ul>
    <li>
      <h2>Yamaha YZF-R1</h2>
      <img src="lien-de-l-image-yamaha.jpg" alt="Image de la Yamaha YZF-R1">
      <p>Description de la moto Yamaha YZF-R1...</p>
    </li>
    <li>
      <h2>Suzuki GSX-R1000</h2>
      <img src="lien-de-l-image-suzuki.jpg" alt="Image de la Suzuki GSX-R1000">
      <p>Description de la moto Suzuki GSX-R1000...</p>
    </li>
    <li>
      <h2>Kawasaki Ninja ZX-10R</h2>
      <img src="lien-de-l-image-kawasaki.jpg" alt="Image de la Kawasaki Ninja ZX-10R">
      <p>Description de la moto Kawasaki Ninja ZX-10R...</p>
    </li>
    <li>
      <h2>Honda CBR1000RR</h2>
      <img src="lien-de-l-image-honda.jpg" alt="Image de la Honda CBR1000RR">
      <p>Description de la moto Honda CBR1000RR...</p>
    </li>
    <!-- Ajoutez ici les autres marques et modèles de motos sportives -->
  </ul>
  <!-- Ajoutez ici d'autres éléments HTML et du contenu pour votre site web -->
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Chatbot pour trouver la moto parfaite</title>
  <!-- Ajoutez ici les balises meta, les liens CSS et autres éléments d'en-tête nécessaires -->
</head>
<body>
  <h1>Chatbot pour trouver la moto parfaite</h1>
  <div id="chatbox">
    <div id="chatlog">
      <!-- Les messages du chatbot et des utilisateurs seront ajoutés dynamiquement ici -->
    </div>
    <input type="text" id="usermsg" placeholder="Entrez votre réponse..." />
    <button onclick="sendMessage()">Envoyer</button>
  </div>

  <script>
    // Fonction pour envoyer un message du chatbot ou de l'utilisateur
    function sendMessage() {
      var usermsg = document.getElementById("usermsg").value;
      var chatlog = document.getElementById("chatlog");
      var chatbotMsg = "<div><strong>Chatbot:</strong> " + getChatbotResponse(usermsg) + "</div>";
      var userMsg = "<div><strong>Vous:</strong> " + usermsg + "</div>";
      chatlog.innerHTML += userMsg + chatbotMsg; // Ajoute le message de l'utilisateur et du chatbot au chatlog
      document.getElementById("usermsg").value = ""; // Réinitialise l'input de l'utilisateur
      chatlog.scrollTop = chatlog.scrollHeight; // Fait défiler le chatlog jusqu'en bas
    }

    // Fonction pour obtenir la réponse du chatbot en fonction de la question de l'utilisateur
    function getChatbotResponse(usermsg) {
      // Implémentez ici la logique pour traiter la question de l'utilisateur et générer la réponse du chatbot
      // Vous pouvez utiliser des conditions, des tableaux, des objets ou d'autres structures de données pour gérer les réponses
      // Vous pouvez également intégrer une API pour le traitement du langage naturel et l'apprentissage automatique afin d'améliorer la précision des réponses du chatbot
      // Cet exemple est une base et nécessitera un développement ultérieur pour ajouter la fonctionnalité d'apprentissage des réponses de chaque visiteur
      // Pour l'instant, le chatbot renvoie une réponse générique
      return "Je suis un chatbot générique et je ne suis pas encore capable d'apprendre des réponses de chaque visiteur. Veuillez m'excuser pour la gêne occasionnée.";
    }
  </script>
</body>
</html>
