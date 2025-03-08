# Bash Configuration

## Instalación

Saque backup del archivo actualmente

```bash
cp ~/.bashrc ~/.bashrc.backup
```

Descargue el archivo

```bash
wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_default.bash
```

Recargue la configuracion

```bash
source ~/.bashrc
```

Todos los comandos

**Configuracion Basica**

```bash
cp ~/.bashrc ~/.bashrc.backup && wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_default.bash && source ~/.bashrc
```

**Configuracion Avanzada**

```bash
cp ~/.bashrc ~/.bashrc.backup && wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_full.sh && source ~/.bashrc
```
