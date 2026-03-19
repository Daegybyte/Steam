# Steam Notes

Useful paths, commands, and tips for working with Steam on Windows.

---

## Console

Open with `Win + R`, then run:

```
steam://open/console
```

---

## Version Control

1. Go to [steamdb.info](https://steamdb.info) and find the game
2. Navigate to **Depots → Manifests**
3. Under **Previously Seen Manifests**, click `Steam Console`
4. Paste the copied command into the Steam console:

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
path\to\skse64_loader.exe
```

### Oblivion Remastered (SKSE)

```
path\to\OblivionRemastered.exe
```
