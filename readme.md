Poner esto:

[merge]

    tool = unityyamlmerge

[mergetool "unityyamlmerge"]

    trustExitCode = false
    cmd = 'C:\\Program Files\\Unity\\Hub\\Editor\\2019.2.12f1\\Editor\\Data\\Tools\\UnityYAMLMerge.exe' merge -p "$BASE" "$REMOTE" "$LOCAL" "$MERGED"

Con tu ruta a UnityYAMLMerge.exe

en
 
 .git(oculto)/config de donde esté el proyecto