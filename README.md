# BL Automation — Bêta privée (CREAZOT)

PWA statique. Code source métier et authentification dans le dépôt privé Seb974/bl-automation.
Accès aux données protégé par Supabase Auth et règles RLS; OCR sur autorisation serveur.
Les clés d'API du navigateur sont exclusivement publishable, jamais de secrets d'Anthropic ou
de Supabase côté client.

**Parcours de connexion :** email + code OTP à **8 chiffres**.

**Service worker :** navigation network-first pour éviter qu'une ancienne page d'authentification
reste affichée malgré le redéploiement.

Attention : cette application est en bêta, sans affichage de BL fictifs après connexion.
