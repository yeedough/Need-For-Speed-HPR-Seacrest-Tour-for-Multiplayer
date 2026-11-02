# Need-For-Speed-HPR-Seacrest-Tour-for-Multiplayer

SEACREST TOUR SWITCHER - version 1

WHAT IT DOES
Switches multiplayer ROADSTERS REBORN to the Seacrest Tour route and back.
The menu name stays ROADSTERS REBORN. Career races, saves, wraps, settings
and the game executable are not changed. This is a utility, not a launcher;
close it and launch the game normally afterward.

HOW TO USE
1. Extract this entire ZIP to a folder. Close the game.
2. Double-click SeacrestSwitcher.exe.
3. Enter 1 for Seacrest Tour, or 2 for original Roadsters Reborn.
4. Confirm the detected game folder with Enter. If needed, paste the folder
   containing NFS11Remastered.exe (Steam > Manage > Browse local files).
5. If Windows requests administrator permission for the game folder,
   approve it to make the selected change. Wait for the success message.
6. Close the tool and launch through Steam as usual.

For a race together, everyone should enable the same patch and use a private
lobby. Select ROADSTERS REBORN; its route should be Seacrest Tour. After playing,
close the game and run the tool again with option 2 to restore the original.

COMPATIBILITY
Windows PC; .NET Framework 4.x (included in normal Windows 10/11 installations).
No Python, PowerShell scripts, installation or separate game launcher needed.
The tested Windows Steam files are recognized by exact SHA-256 hashes.
Different game versions, console copies, and conflicting mods are not supported.
EA-store compatibility has not been tested; an identical file set can pass the
same checks, but no compatibility is promised for other versions or stores.
The utility stops on unsupported files rather than guessing offsets.
One complete online race on two identically patched Steam PCs was reported
successful. Broader multiplayer configurations are not yet tested.

BACKUP AND RESTORE
Enabling keeps an original archive backup next to CHALLENGEINSTANCES.BNDL:
  GAMELOGIC\CHALLENGEINSTANCES.BNDL.seacrest-original.bak
It never overwrites an unexpected existing backup. Keep that backup.
Restoring reconstructs and verifies the exact original archive, so it also
works if the backup or an earlier extracted copy of this utility was lost.
Only the recognized original and recognized Seacrest candidate are accepted.
Restore does not require other game files to match, allowing recovery if
another file has since changed. It never restores or edits your saves.

TROUBLESHOOTING
- Game open: quit normally and retry.
- Unsupported/modified file: stop; this tool does not combine other mods.
- Folder not found: paste the full actual game folder, not a shortcut.
- Access denied: use Windows' normal administrator approval. If still blocked,
  stop and report the error. Do not change security or script policies.
- This small custom utility is unsigned. Windows may show an unfamiliar-app
  warning. No signing or security-policy changes are performed by this tool.
- An interrupted switch leaves a verified original backup; reopen the tool
  and choose restore. If it reports an unknown archive, preserve the file and
  seek help instead of overwriting it blindly.
