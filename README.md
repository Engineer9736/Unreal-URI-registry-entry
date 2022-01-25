# Unreal-URI-registry-entry


Put in a .reg file, adjust the paths, and run.


`
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\unreal]
@="URL:unreal"
"URL Protocol"=""

[HKEY_CLASSES_ROOT\unreal\shell]

[HKEY_CLASSES_ROOT\unreal\shell\open]

[HKEY_CLASSES_ROOT\unreal\shell\open\command]
@="\"D:\\documenten\\Games\\UnrealTournament\\System\\UnrealTournament.exe\" \"%1\""
"Executable"="D:\\documenten\\Games\\UnrealTournament\\System\\UnrealTournament.exe"
`
