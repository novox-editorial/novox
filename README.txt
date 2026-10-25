NOVOX — starter de connexion Supabase

CONTENU
- index.html : page NOVOX avec formulaires d'inscription/connexion, profil simple, affichage des articles publiés et demande d'abonnement en attente.
- supabase-config.js : paramètres à remplir avec l'URL du projet et la clé publique Supabase.

AVANT PUBLICATION
1. Ouvre supabase-config.js dans un éditeur de texte.
2. Remplace COLLE_ICI_LA_PROJECT_URL par la Project URL de Supabase.
3. Remplace COLLE_ICI_LA_CLE_PUBLISHABLE par la publishable key (ou ancienne clé anon).
4. Ne mets jamais de clé secret/service_role dans les fichiers du site.
5. Teste sur une copie ou une branche avant de remplacer le site publié.

LIMITES ACTUELLES
- Authentification et affichage des articles : intégration de base, à tester avec les paramètres et politiques réels.
- Profil : modification du nom uniquement ; photo non intégrée ici.
- Abonnements : enregistrement avec active=false uniquement. Aucun email de confirmation ni newsletter envoyé.
- Les formulaires d'opinion, NOVOX TV, jeux, notifications et tableau de bord ne sont pas encore implémentés.
- Les fichiers doivent être servis via HTTP(S); les politiques RLS Supabase restent obligatoires.
