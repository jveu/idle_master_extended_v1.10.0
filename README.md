# idle_master_extended_v1.10.0
A simple Steam idling tool that launches a selected Steam game using its Application ID, allowing the game to remain running in the background for Steam playtime tracking.

# Steam Hour Farming Guide

A simple guide to setting up and running the idle batch file.

## 1. Set Up `idle.txt`

Open `idle.txt` in a text editor such as Notepad.

Add the following command:

```text
start steam-dile.exe APPID
```

Replace `APPID` with the Steam Application ID of the game you want to use.

**Example:**

```text
start steam-dile.exe 221100
```

## 2. Find the Steam App ID

Go to the game's Steam Store page and check the URL.

Steam Store URLs generally use the following format:

```text
https://store.steampowered.com/app/APPID/
```

The number in the URL is the game's **Application ID**.

### Example: Wasteland 2

Steam Store URL:

```text
https://store.steampowered.com/app/240760/
```

The Application ID is:

```text
240760
```

So the command would be:

```text
start steam-dile.exe 240760
```

## 3. Save the File as `.bat`

After entering your command:

1. Click **File → Save As**.
2. Change the filename from `idle.txt` to `idle.bat`.
3. Set **Save as type** to **All Files (*.*)** if necessary.
4. Click **Save**.

> **Important:** Make sure the file is named `idle.bat`, not `idle.bat.txt`.

## 4. Run the File

Once the file has been saved as `idle.bat`, simply **double-click it** to run.

The batch file will execute the command using the Steam Application ID you entered.

---

**Originally created by jveu. I did not create the original script; I have only updated and improved it to make it easier to use.**
