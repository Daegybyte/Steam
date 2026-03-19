# Steam Notes

Useful paths, commands, and tips for working with Steam on Windows.

---

## Console

Open with `Win + R`, then run:

```
steam://open/console
```

---

## Game Version Control

1. Go to [steamdb.info](https://steamdb.info) and find the game
2. Navigate to **Depots → Manifests**
3. Under **Previously Seen Manifests**, click `Steam Console`
4. Paste the copied command into the Steam console:
5. Wait for the download to complete, then copy the new files to your game directory **NOTE: Steam
   Console will tell you where the files are downloaded**

```
download_depot $APP_ID $DEPOT_ID $MANIFEST_ID
```

### Skyrim Special Edition

```
download_depot 2623190 2623191 3680196445693511195
```

### Oblivion Remastered V1.1

```
download_depot 2623190 2623191 3680196445693511195
```

---

## Alternative Launchers

Right-click game → **Properties → Launch Options**

---

### Skyrim (SKSE)

```
"C:\Program Files (x86)\Steam\steamapps\common\Skyrim Special Edition\skse64_loader.exe" -- %command%
```

### Oblivion Remastered (SKSE)

```
"C:\Program Files (x86)\Steam\steamapps\common\Oblivion Remastered\OblivionRemastered\Binaries\Win64\obse64_loader.exe" -- %command%
```

### Morrowind (OpenMW)

**BE SURE TO UPDATE PATH TO REFLECT VERSION NUMBER**

```
"C:\Program Files\OpenMW 0.50.0\openmw.exe" %command%
```
