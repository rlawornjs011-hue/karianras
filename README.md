# Lumi Server Launcher

A private Windows launcher for a whitelisted Minecraft: Java Edition server shared by a small group of friends (about 10 players).

It is a customized build of the open-source [Helios Launcher](https://github.com/dscalzi/HeliosLauncher). The launcher installs one fixed modpack — **Prominence II: Hasturian Era 4.1.1** (Fabric, Minecraft 1.20.1) with a Korean translation and a few companion add-ons — verifies the files, launches the game and connects to our server.

## Sign-in

- Players sign in with **their own licensed Microsoft account** through Microsoft's own login page (OAuth 2.0 authorization code flow), followed by Xbox Live, XSTS and Minecraft services authentication.
- Requested scopes: `XboxLive.signin offline_access`
- Redirect URI: `https://login.microsoftonline.com/common/oauth2/nativeclient`
- The launcher never sees passwords. There is no backend that collects accounts or tokens; tokens are stored locally on each player's PC.
- The game server runs in online mode with a whitelist.

## What it does not do

- It does not bypass authentication, license checks or any safety features.
- It does not offer offline/cracked play.
- It is shared only with the server's members and is not published as a public download.

## Credits

Based on Helios Launcher by Daniel Scalzi and contributors. Prominence II is made by its respective authors; mods are downloaded from their official CurseForge/Modrinth sources.

---

# 루미서버 런처

친구 10명 정도가 함께 쓰는 화이트리스트 마인크래프트 자바 서버 전용 Windows 런처예요. 오픈소스 Helios Launcher를 바탕으로 만들었어요. Prominence II 4.1.1(Fabric 1.20.1) 한글판 모드팩을 설치하고 검사한 뒤 게임을 실행하고 서버에 접속해요.

각자 자기 정품 Microsoft 계정으로 Microsoft 공식 로그인 창에서 로그인해요. 런처는 비밀번호를 보지 않고, 계정이나 토큰을 모으는 서버도 없어요.
