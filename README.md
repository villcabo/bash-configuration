# Bash Configuration

## Instalación

Saque backup del archivo actualmente

```bash
cp ~/.bashrc ~/.bashrc.backup
```

Descargue el archivo

```bash
wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_default.sh
```

Recargue la configuracion

```bash
source ~/.bashrc
```

Todos los comandos

**Configuracion Basica**

```bash
cp ~/.bashrc ~/.bashrc.backup && wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_default.sh && source ~/.bashrc
```

**Configuracion Avanzada**

```bash
cp ~/.bashrc ~/.bashrc.backup && wget -q -O ~/.bashrc https://raw.githubusercontent.com/villcabo/bash-configuration/main/bash_full.sh && source ~/.bashrc
```
