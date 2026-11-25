👑 RG RIFAT 07

FREE FIRE PLAYER INFO SYSTEM

A Powerful • Fast • Vercel-Ready Flask API

A modern and well-structured Free Fire Player Information API, designed to retrieve detailed player and account information through a simple API request.

---

👨‍💻 PROJECT BRANDING

- Owner: @RG_RIFAT_07
- Telegram Channel: https://t.me/HYPER_APEX_PRIME
- Telegram Group: https://t.me/RIFAT_X_HYPER

---

🚀 MAIN API ENDPOINT

Endpoint:

GET /info?uid=PLAYER_UID

Retrieve available Free Fire player information using a single UID request.

📋 PLAYER INFORMATION

The "/info" endpoint provides the following information whenever available in the game response:

- Player Identity: Nickname, UID, region and account details.
- Rank Information: Current rank and rank-related statistics.
- Account Information: Account creation date and last activity.
- Activity Status: Relative activity time.
- Profile Assets: Avatar, banner and title.
- Character Profile: Character information and profile details.
- Equipped Outfits: Outfit IDs and corresponding names.
- Weapon Skins: Available weapon skin information.
- Selected Items: Selected equipment and item slots.
- Pet Information: Pet details and related information.
- Guild Information: Guild name, ID and other available details.
- Guild Leader: Leader identity and related information.
- Social Information: Available social profile details.

Note: Information depends on the fields returned by the game API.

---

⚙️ INSTALLATION & DEPLOYMENT

1. Install Dependencies

pip install -r requirements.txt

2. Run Locally

python app.py

3. Vercel Deployment

The project includes "vercel.json" and is structured for Vercel deployment.

Upload the project to your repository and connect it to Vercel.

---

🔐 JWT AUTHENTICATION SYSTEM

- Uses the project's existing direct JWT/login flow.
- Maintains the existing authentication logic.
- External JWT URL is retained as optional configuration metadata.
- "/info" does not require an external JWT URL.

---

✨ PROJECT HIGHLIGHTS

- Fast Flask-based API
- Simple UID-based requests
- Organized player information
- Detailed player profile response
- Vercel-ready deployment structure
- Existing direct JWT authentication flow

---

RG RIFAT 07
POWERED BY RG RIFAT

📢 Channel: https://t.me/HYPER_APEX_PRIME
💬 Group: https://t.me/RIFAT_X_HYPER