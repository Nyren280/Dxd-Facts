High School DxD Facts

A GitHub-hosted database for a Discord webhook bot that sends one unique High School DxD fact daily.

Features

* 📅 Daily rotating facts
* 🔄 No repeated facts until a category is completed
* 📚 Multiple databases/categories
* 🛠️ Easy expansion by adding new JSON files
* 🌐 GitHub-hosted data
* 🤖 Designed for Scriptable Discord webhook automation

Repository Structure

highschool-dxd-facts/
├── README.md
├── database.json
├── progress.json
├── characters.json
├── devils.json
├── fallen_angels.json
├── angels.json
├── dragons.json
├── sacred_gears.json
├── abilities.json
├── factions.json
├── clans.json
├── locations.json
├── battles.json
├── lore.json
├── light_novel.json
├── anime.json
└── trivia.json

Categories

Category	Description
Characters	Character profiles and facts
Devils	Devil characters, ranks, and clans
Fallen Angels	Fallen angel information
Angels	Angel hierarchy and lore
Dragons	Dragons and dragon-related facts
Sacred Gears	Sacred Gear users and abilities
Abilities	Powers, techniques, and skills
Factions	Groups and organizations
Clans	Families and bloodlines
Locations	Important places
Battles	Major fights and events
Lore	Worldbuilding information
Light Novel	Light novel volumes and story details
Anime	Anime adaptation facts
Trivia	Random High School DxD facts

JSON Format

Each database contains an array of facts.

Example:

{
  "id": 1,
  "name": "Example",
  "fact": "Example High School DxD fact.",
  "spoiler": false,
  "source": "Light Novel"
}

Adding New Categories

1. Create a new JSON file.
2. Add it to database.json.
3. Push changes to GitHub.
4. The bot will automatically detect it.

No script changes required.

Disclaimer

This project is a fan-made database for informational and entertainment purposes.

High School DxD belongs to its respective creators and publishers.