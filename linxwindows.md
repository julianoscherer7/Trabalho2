Windows:
Sistemas de Arquivos Comuns: NTFS, FAT32, exFAT.
Estrutura de Diretórios: Usa barras invertidas () e letras de unidade (ex.: C:).
Permissões e Segurança: ACLs detalhadas, permissões herdadas.
Características Avançadas: Compressão, criptografia (EFS), arquivos dispersos, journaling.
Compatibilidade: NTFS amplamente suportado, FAT32 e exFAT compatíveis com muitos sistemas operacionais.
Linux:
Sistemas de Arquivos Comuns: ext4, Btrfs, XFS, ReiserFS.
Estrutura de Diretórios: Usa barras normais (/) e uma única árvore de diretórios começando em /.
Permissões e Segurança: Modelo simples (proprietário, grupo, outros), ACLs, SELinux/AppArmor.
Características Avançadas: Journaling, snapshots (Btrfs), subvolumes, links simbólicos/hard links.
Compatibilidade: ext4 não suportado nativamente pelo Windows; ferramentas de terceiros necessárias para compatibilidade.
Resumo:
Windows usa NTFS, com uma estrutura de diretórios baseada em letras de unidade e ACLs detalhadas, enquanto Linux utiliza vários sistemas de arquivos (como ext4 e Btrfs) com uma estrutura de diretórios unificada e permissões simples mas eficazes.
