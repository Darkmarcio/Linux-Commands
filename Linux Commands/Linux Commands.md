
Comandos Básicos de Navegação e Manipulação de Arquivos
ls
Lista os arquivos e diretórios no diretório atual.
Exemplo: ls -l (lista em formato longo), ls -a (mostra arquivos ocultos).

cd
Muda o diretório atual.
Exemplo: cd /home/usuario (navega para o diretório /home/usuario), cd .. (volta um nível).

pwd
Mostra o caminho completo do diretório atual.

mkdir
Cria um novo diretório.
Exemplo: mkdir nova_pasta.

rmdir
Remove um diretório vazio.
Exemplo: rmdir pasta_vazia.

touch
Cria um arquivo vazio ou atualiza a data de modificação de um arquivo existente.
Exemplo: touch arquivo.txt.

cp
Copia arquivos ou diretórios.
Exemplo: cp arquivo.txt /outro/diretorio.

mv
Move ou renomeia arquivos ou diretórios.
Exemplo: mv arquivo.txt novo_nome.txt.

rm
Remove arquivos ou diretórios.
Exemplo: rm arquivo.txt, rm -r pasta (remove recursivamente).

cat
Exibe o conteúdo de um arquivo.
Exemplo: cat arquivo.txt.

more / less
Exibe o conteúdo de um arquivo paginado (útil para arquivos grandes).
Exemplo: less arquivo.txt.

head
Mostra as primeiras linhas de um arquivo.
Exemplo: head -n 10 arquivo.txt (mostra as 10 primeiras linhas).

tail
Mostra as últimas linhas de um arquivo.
Exemplo: tail -n 10 arquivo.txt (mostra as 10 últimas linhas).

find
Procura arquivos e diretórios.
Exemplo: find /home -name "arquivo.txt".

grep
Procura por padrões em arquivos ou saídas de comandos.
Exemplo: grep "palavra" arquivo.txt.

Comandos de Gerenciamento de Processos
ps
Lista os processos em execução.
Exemplo: ps aux (mostra todos os processos).

top
Mostra os processos em tempo real, com uso de CPU e memória.

kill
Encerra um processo.
Exemplo: kill 1234 (encerra o processo com PID 1234).

killall
Encerra todos os processos com um determinado nome.
Exemplo: killall firefox.

bg / fg
Coloca um processo em segundo plano (bg) ou traz para o primeiro plano (fg).

jobs
Lista os processos em segundo plano.

Comandos de Rede
ping
Testa a conectividade com um endereço IP ou domínio.
Exemplo: ping google.com.

ifconfig / ip
Mostra informações sobre as interfaces de rede.
Exemplo: ifconfig ou ip addr.

netstat
Exibe conexões de rede, portas abertas e estatísticas.
Exemplo: netstat -tuln.

ssh
Conecta a um servidor remoto via SSH.
Exemplo: ssh usuario@host.

scp
Copia arquivos entre máquinas via SSH.
Exemplo: scp arquivo.txt usuario@host:/caminho.

wget / curl
Baixa arquivos da internet.
Exemplo: wget https://exemplo.com/arquivo.zip.

Comandos de Permissões e Propriedades
chmod
Altera as permissões de arquivos ou diretórios.
Exemplo: chmod 755 arquivo.txt.

chown
Altera o proprietário de um arquivo ou diretório.
Exemplo: chown usuario:grupo arquivo.txt.

chgrp
Altera o grupo de um arquivo ou diretório.
Exemplo: chgrp grupo arquivo.txt.

Comandos de Sistema
uname
Mostra informações sobre o sistema.
Exemplo: uname -a (mostra todas as informações).

df
Mostra o uso de espaço em disco.
Exemplo: df -h (em formato legível).

du
Mostra o uso de espaço em disco de arquivos e diretórios.
Exemplo: du -sh pasta.

free
Mostra o uso de memória RAM.
Exemplo: free -h.

shutdown
Desliga ou reinicia o sistema.
Exemplo: shutdown now (desliga imediatamente), shutdown -r (reinicia).

reboot
Reinicia o sistema.

date
Mostra ou define a data e hora do sistema.
Exemplo: date.

tar
Cria ou extrai arquivos compactados.
Exemplo: tar -cvf arquivo.tar pasta (cria), tar -xvf arquivo.tar (extrai).

gzip / gunzip
Comprime ou descomprime arquivos.
Exemplo: gzip arquivo.txt, gunzip arquivo.txt.gz.

alias
Cria atalhos para comandos.
Exemplo: alias ll='ls -la'.

Comandos de Usuários e Grupos
useradd / adduser
Adiciona um novo usuário.
Exemplo: useradd novo_usuario.

passwd
Altera a senha de um usuário.
Exemplo: passwd usuario.

usermod
Modifica as propriedades de um usuário.
Exemplo: usermod -aG grupo usuario.

userdel
Remove um usuário.
Exemplo: userdel usuario.

groupadd
Cria um novo grupo.
Exemplo: groupadd novo_grupo.

groupdel
Remove um grupo.
Exemplo: groupdel grupo.

Outros Comandos Úteis
history
Mostra o histórico de comandos executados.

man
Exibe o manual de um comando.
Exemplo: man ls.

echo
Exibe uma mensagem na tela.
Exemplo: echo "Olá, mundo!".

which
Mostra o caminho completo de um executável.
Exemplo: which ls.

ln
Cria links simbólicos ou hard links.
Exemplo: ln -s /caminho/original /caminho/link.

diff
Compara dois arquivos e mostra as diferenças.
Exemplo: diff arquivo1.txt arquivo2.txt.

wc
Conta linhas, palavras e caracteres em um arquivo.
Exemplo: wc arquivo.txt.

sort
Ordena as linhas de um arquivo.
Exemplo: sort arquivo.txt.

uniq
Remove linhas duplicadas de um arquivo.
Exemplo: uniq arquivo.txt.

1. Comandos de Navegação e Manipulação de Arquivos
ls: Lista arquivos e diretórios.

cd: Muda o diretório atual.

pwd: Mostra o diretório atual.

mkdir: Cria um diretório.

rmdir: Remove um diretório vazio.

touch: Cria um arquivo vazio ou atualiza o timestamp.

cp: Copia arquivos ou diretórios.

mv: Move ou renomeia arquivos ou diretórios.

rm: Remove arquivos ou diretórios.

cat: Exibe o conteúdo de um arquivo.

more / less: Exibe o conteúdo de um arquivo paginado.

head: Mostra as primeiras linhas de um arquivo.

tail: Mostra as últimas linhas de um arquivo.

find: Procura arquivos e diretórios.

grep: Procura por padrões em arquivos.

ln: Cria links simbólicos ou hard links.

chmod: Altera permissões de arquivos.

chown: Altera o proprietário de um arquivo.

chgrp: Altera o grupo de um arquivo.

tar: Cria ou extrai arquivos compactados.

gzip / gunzip: Comprime ou descomprime arquivos.

zip / unzip: Trabalha com arquivos ZIP.

rsync: Sincroniza arquivos e diretórios.

diff: Compara dois arquivos.

wc: Conta linhas, palavras e caracteres.

sort: Ordena linhas de um arquivo.

uniq: Remove linhas duplicadas.

tee: Redireciona a saída para um arquivo e para a tela.

split: Divide um arquivo em partes menores.

stat: Mostra informações detalhadas sobre um arquivo.

2. Comandos de Gerenciamento de Processos
ps: Lista processos em execução.

top: Mostra processos em tempo real.

htop: Versão interativa do top.

kill: Encerra um processo.

killall: Encerra processos por nome.

pkill: Encerra processos por padrão.

bg: Coloca um processo em segundo plano.

fg: Traz um processo para o primeiro plano.

jobs: Lista processos em segundo plano.

nohup: Executa um processo que não é interrompido ao sair do terminal.

nice: Altera a prioridade de um processo.

renice: Altera a prioridade de um processo em execução.

pgrep: Procura processos por nome.

pstree: Mostra processos em formato de árvore.

3. Comandos de Rede
ping: Testa a conectividade com um host.

ifconfig / ip: Configura interfaces de rede.

netstat: Mostra conexões de rede e estatísticas.

ss: Versão moderna do netstat.

ssh: Conecta a um servidor remoto.

scp: Copia arquivos via SSH.

rsync: Sincroniza arquivos via rede.

wget / curl: Baixa arquivos da internet.

ftp / sftp: Conecta a servidores FTP.

nslookup / dig: Consulta DNS.

traceroute: Mostra o caminho dos pacotes até um host.

nmcli: Gerencia conexões de rede (NetworkManager).

iwconfig: Configura interfaces wireless.

hostname: Mostra ou define o nome do host.

route: Mostra ou configura a tabela de roteamento.

arp: Mostra a tabela ARP.

4. Comandos de Sistema
uname: Mostra informações do sistema.

df: Mostra o uso de espaço em disco.

du: Mostra o uso de espaço em diretórios.

free: Mostra o uso de memória.

uptime: Mostra o tempo de atividade do sistema.

shutdown: Desliga ou reinicia o sistema.

reboot: Reinicia o sistema.

date: Mostra ou define a data e hora.

cal: Mostra um calendário.

alias: Cria atalhos para comandos.

unalias: Remove um alias.

history: Mostra o histórico de comandos.

which: Mostra o caminho de um executável.

whereis: Localiza arquivos de um programa.

locate: Encontra arquivos rapidamente.

updatedb: Atualiza o banco de dados do locate.

cron / crontab: Agenda tarefas.

systemctl: Gerencia serviços (systemd).

journalctl: Visualiza logs do systemd.

dmesg: Mostra mensagens do kernel.

lspci: Lista dispositivos PCI.

lsusb: Lista dispositivos USB.

lsmod: Lista módulos do kernel carregados.

modprobe: Gerencia módulos do kernel.

5. Comandos de Usuários e Grupos
useradd / adduser: Adiciona um usuário.

userdel: Remove um usuário.

usermod: Modifica um usuário.

passwd: Altera a senha de um usuário.

groupadd: Adiciona um grupo.

groupdel: Remove um grupo.

groups: Mostra os grupos de um usuário.

id: Mostra informações do usuário e grupos.

su: Muda para outro usuário.

sudo: Executa comandos como superusuário.

visudo: Edita o arquivo de configuração do sudo.

who: Mostra usuários logados.

w: Mostra informações sobre usuários logados.

last: Mostra o histórico de logins.

finger: Mostra informações sobre usuários.

6. Comandos de Desenvolvimento e Scripting
gcc: Compilador C.

g++: Compilador C++.

python: Interpretador Python.

perl: Interpretador Perl.

bash: Shell Bash.

sh: Shell Bourne.

awk: Linguagem para processamento de texto.

sed: Editor de fluxo de texto.

make: Ferramenta de compilação.

git: Controle de versão.

ssh-keygen: Gera chaves SSH.

curl: Ferramenta para transferência de dados.

jq: Processa JSON na linha de comando.

docker: Gerencia contêineres Docker.

kubectl: Gerencia clusters Kubernetes.

7. Comandos de Segurança
chroot: Muda o diretório raiz de um processo.

iptables: Configura regras de firewall.

ufw: Interface simplificada para o iptables.

openssl: Ferramenta de criptografia.

gpg: Criptografia e assinatura de arquivos.

ssh-agent: Gerencia chaves SSH.

fail2ban: Bloqueia tentativas de invasão.

auditd: Auditoria do sistema.

selinux: Ferramentas para SELinux.

8. Comandos de Monitoramento e Desempenho
vmstat: Mostra estatísticas do sistema.

iostat: Mostra estatísticas de I/O.

mpstat: Mostra estatísticas de CPU.

sar: Coleta e relata estatísticas do sistema.

lsof: Lista arquivos abertos.

strace: Rastreia chamadas de sistema.

ltrace: Rastreia chamadas de biblioteca.

perf: Ferramenta de análise de desempenho.

9. Comandos de Backup e Restauração
dd: Copia e converte arquivos.

rsync: Sincroniza arquivos.

tar: Cria backups compactados.

dump / restore: Ferramentas de backup.

btrfs: Gerencia sistemas de arquivos Btrfs.

zfs: Gerencia sistemas de arquivos ZFS.

10. Comandos de Virtualização e Contêineres
virsh: Gerencia máquinas virtuais (KVM).

virt-manager: Interface gráfica para KVM.

docker: Gerencia contêineres Docker.

podman: Alternativa ao Docker.

kubectl: Gerencia clusters Kubernetes.

vagrant: Gerencia ambientes de desenvolvimento virtualizados.

11. Comandos de Texto e Editores
nano: Editor de texto simples.

vim / vi: Editor de texto avançado.

emacs: Editor de texto poderoso.

sed: Editor de fluxo de texto.

awk: Linguagem para processamento de texto.

cut: Extrai colunas de texto.

paste: Combina linhas de arquivos.

tr: Traduz ou remove caracteres.

fmt: Formata texto.

12. Comandos de Multimídia
ffmpeg: Conversão e edição de vídeo/áudio.

mplayer: Reprodutor de mídia.

mpv: Reprodutor de mídia moderno.

imagemagick: Manipulação de imagens.

13. Comandos de Impressão
lp: Envia arquivos para impressão.

lpstat: Mostra o status da impressora.

lprm: Remove trabalhos de impressão.

14. Comandos de Desenvolvimento de Kernel
make: Compila o kernel.

modprobe: Gerencia módulos do kernel.

insmod: Carrega módulos do kernel.

rmmod: Remove módulos do kernel.

depmod: Gera dependências de módulos.

15. Comandos de Gerenciamento de Pacotes
apt: Gerencia pacotes no Debian/Ubuntu.

yum / dnf: Gerencia pacotes no CentOS/Fedora.

pacman: Gerencia pacotes no Arch Linux.

zypper: Gerencia pacotes no openSUSE.

rpm: Gerencia pacotes RPM.

dpkg: Gerencia pacotes DEB.

16. Comandos de Terminal e Shell
clear: Limpa a tela do terminal.

reset: Reinicia o terminal.

exit: Sai do terminal.

echo: Exibe texto na tela.

printf: Exibe texto formatado.

read: Lê entrada do usuário.

source: Executa um script no shell atual.

exec: Substitui o shell atual por um comando.

export: Define variáveis de ambiente.

env: Mostra variáveis de ambiente.

set: Define opções do shell.

unset: Remove variáveis ou funções.

17. Comandos de Automação e Scripting
cron: Agenda tarefas.

at: Agenda uma tarefa única.

bash: Executa scripts Bash.

expect: Automatiza interações com programas.

xargs: Constrói e executa comandos a partir de entrada.

18. Comandos de Sistema de Arquivos
mount: Monta sistemas de arquivos.

umount: Desmonta sistemas de arquivos.

fsck: Verifica e repara sistemas de arquivos.

mkfs: Cria um sistema de arquivos.

tune2fs: Ajusta parâmetros do sistema de arquivos ext.

resize2fs: Redimensiona sistemas de arquivos ext.

df: Mostra o uso de espaço em disco.

du: Mostra o uso de espaço em diretórios.

19. Comandos de Virtualização de Terminal
screen: Gerencia sessões de terminal.

tmux: Gerencia sessões de terminal avançadas.

20. Comandos de Logs
dmesg: Mostra mensagens do kernel.

journalctl: Visualiza logs do systemd.

tail -f: Monitora logs em tempo real.

logger: Envia mensagens para o syslog.

21. Comandos de Desenvolvimento Web
curl: Ferramenta para transferência de dados.

wget: Baixa arquivos da web.

lynx: Navegador de terminal.

nginx: Servidor web.

apachectl: Gerencia o servidor Apache.

certbot: Obtém certificados SSL.

22. Comandos de Banco de Dados
mysql: Cliente MySQL.

psql: Cliente PostgreSQL.

sqlite3: Cliente SQLite.

mongodb: Cliente MongoDB.

23. Comandos de Virtualização de Rede
brctl: Gerencia bridges de rede.

ip: Gerencia interfaces de rede.

tcpdump: Captura pacotes de rede.

wireshark: Analisa pacotes de rede.

24. Comandos de Desenvolvimento de Software
gdb: Depurador GNU.

strace: Rastreia chamadas de sistema.

valgrind: Ferramenta de análise de memória.

make: Ferramenta de compilação.

cmake: Ferramenta de build.

autoconf: Gera scripts de configuração.

automake: Gera Makefiles.

25. Comandos de Segurança de Rede
nmap: Varre portas de rede.

netcat: Ferramenta de rede versátil.

openssl: Ferramenta de criptografia.

ssh: Conexão segura.

scp: Copia arquivos via SSH.

sftp: Transferência segura de arquivos.

26. Comandos de Virtualização de Armazenamento
lvm: Gerencia volumes lógicos.

mdadm: Gerencia RAID.

iscsiadm: Gerencia iSCSI.

gluster: Gerencia sistemas de arquivos distribuídos.

27. Comandos de Virtualização de Contêineres
docker: Gerencia contêineres Docker.

podman: Alternativa ao Docker.

buildah: Constrói imagens de contêineres.

skopeo: Manipula imagens de contêineres.

28. Comandos de Virtualização de Máquinas
qemu: Emulador de máquinas virtuais.

virt-manager: Interface gráfica para KVM.

virsh: Cliente de linha de comando