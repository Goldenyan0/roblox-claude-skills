# roblox-claude-skills

10 skills pour [Claude Code](https://claude.com/claude-code) (ils marchent aussi avec Codex et les autres agents qui lisent les fichiers `SKILL.md`) pour développer des jeux Roblox avec méthode : code sécurisé, données qui ne se perdent pas, UI qui s'adapte à tous les écrans, performances mesurées.

| Skill | À quoi il sert |
|---|---|
| `roblox-debugging` | Déboguer avec une méthode fixe (reproduire, isoler, expliquer, vérifier) au lieu de deviner |
| `roblox-secure-remotes` | Écrire ou relire des RemoteEvents / RemoteFunctions avec le serveur comme seule autorité |
| `roblox-datastore-safety` | Sauvegarde des joueurs : verrou de session, réessais, BindToClose, migrations, reçus d'achat |
| `roblox-anti-exploit-review` | Audit défensif des risques de triche, avec détection côté serveur |
| `roblox-monetization-compliance` | Game passes, developer products, ProcessReceipt, objets aléatoires payants et règles Roblox |
| `roblox-performance-audit` | Trouver les ralentissements avec des mesures (MicroProfiler, mémoire, réseau, mobile) |
| `roblox-ui-builder` | UI adaptée à tous les écrans : zones sûres, animations, accessibilité |
| `roblox-asset-import` | Importer modèles et textures à la bonne échelle, dans les budgets de triangles et de textures |
| `roblox-system-builder` | Construire une fonctionnalité complète (inventaire, boutique, quêtes...) de bout en bout |
| `roblox-vault-research` | Consulter automatiquement une base de notes Roblox avant d'écrire du code |

## Installation (2 minutes)

1. Téléchargez le dépôt (bouton **Code > Download ZIP**, ou `git clone`).
2. Copiez les dossiers `roblox-*` dans le dossier des skills de Claude Code :
   - Windows : `%USERPROFILE%\.claude\skills\`
   - macOS / Linux : `~/.claude/skills/`
3. Redémarrez Claude Code. Les skills se déclenchent tout seuls quand vous parlez de Roblox (« mon remote est exploitable ? », « le jeu lag sur téléphone »...).

## Base de notes (optionnelle)

Les skills peuvent s'appuyer sur une base de notes Roblox au format Obsidian (dossiers `02 Luau Scripting/`, `03 Architecture and Networking/`, etc., avec un fichier `VAULT_INDEX.md` à la racine).

- Si vous en avez une, remplacez `{{ROBLOX_VAULT}}` dans les `SKILL.md` par son chemin, ou définissez la variable d'environnement `ROBLOX_VAULT`.
- Sinon, les skills fonctionnent quand même : leur méthode et leurs règles sont dans le `SKILL.md`.

## Licence

MIT
