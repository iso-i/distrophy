# distrophy
distributed authed backup storage

Backups MUST be automated, (or they are just a snapshot.)
borgbackup is ideal, though other backup systems also exist.

"Quis custodiet ipsos custodes?" 
distrophy {eventually} ensures that there are n+1 copies of your backups,
encrypted and spread out between other nodes. Nodes may be computers in
another data centre, another country, a friend's basement; anywhere that
is, {at least} sporadically online.

