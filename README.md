# PORTFOLIO

site:
  title: "Mon Portfolio Professionnel"
  description: "Présentation de mes compétences et réalisations"
  url: "https://www.monsite.com"
  layout: "responsive"
  charte_graphique:
    couleurs:
      primaire: "#3498db"
      secondaire: "#2ecc71"
      background: "#ecf0f1"
      texte: "#2c3e50"
    typographie:
      titre: "Arial, sans-serif"
      texte: "Georgia, serif"
    images:
      logo: "/images/logo.png"
      photo_profil: "/images/photo-profil.jpg"
  
  pages:
    - nom: "Accueil"
      url: "/"
      contenu:
        - type: "texte"
          contenu: |
            <h1>Prénom Nom</h1>
            <p>Accroche captivante qui résume votre activité et vos compétences.</p>
            <p>Je suis un professionnel passionné par le développement web, avec une expertise dans la création de solutions adaptées aux besoins des clients.</p>
        - type: "image"
          src: "/images/photo-illustration.jpg"
    
    - nom: "Compétences"
      url: "/competences"
      contenu:
        - type: "section"
          titre: "Développement"
          items:
            - nom: "HTML"
              niveau: "★★★★☆"
            - nom: "CSS"
              niveau: "★★★☆☆"
            - nom: "JavaScript"
              niveau: "★★☆☆☆"
        - type: "section"
          titre: "Bureautique"
          items:
            - nom: "Microsoft Word"
              niveau: "★★★★☆"
            - nom: "Microsoft Excel"
              niveau: "★★★☆☆"
    
    - nom: "Réalisations"
      url: "/realisations"
      contenu:
        - type: "projet"
          titre: "Site de e-commerce"
          description: "Création d'un site web e-commerce pour une entreprise de mode."
          image: "/images/projet-ecommerce.jpg"
          documents:
            - nom: "Procédure d'installation"
              lien: "/documents/procedure-installation.pdf"
            - nom: "Captures d'écran"
              lien: "/images/ecommerce/screenshots.png"
    
    - nom: "Formation"
      url: "/formation"
      contenu:
        - type: "formation"
          nom: "Développeur Web"
          etablissement: "École de Formation en Informatique"
          date_debut: "2022-09-01"
          date_fin: "2023-06-30"
          lieu: "Paris, France"
          contenu: "Apprentissage des technologies web : HTML, CSS, JavaScript, PHP, SQL."
          cv_pdf: "/documents/cv.pdf"
    
    - nom: "Contact"
      url: "/contact"
      contenu:
        - type: "formulaire"
          elements:
            - type: "input"
              nom: "nom"
              placeholder: "Votre nom"
              obligatoire: true
            - type: "input"
              nom: "email"
              placeholder: "Votre adresse e-mail"
              obligatoire: true
            - type: "input"
              nom: "objet"
              placeholder: "Objet du message"
              obligatoire: true
            - type: "textarea"
              nom: "message"
              placeholder: "Votre message"
              obligatoire: true
            - type: "captcha"
              nom: "captcha"
              obligatoire: true
        - type: "action"
          action: "envoyer"
          url: "mailto:contact@monsite.com"
          methode: "POST"
  
  footer:
    texte: "© 2024 Mon Portfolio - Tous droits réservés"
    liens:
      - titre: "Mentions légales"
        url: "/mentions-legales"
      - titre: "Politique de confidentialité"
        url: "/politique-confidentialite"
