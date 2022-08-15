# Como compilar el tema yaru en Rocky Linux 9 Workstation

### 1. Instalar dependencias
`$ su`

```#dnf install gtk3-devel git sassc python3 python3-pip```

### 2. Instalar meson y ninja con pip3

```#pip3 install meson```

```#pip3 install ninja```


### 3. Cambiar al directorio /usr/local/src y clonar el repositorio

```#cd /usr/local/src```

```#git clone https://github.com/ubuntu/yaru.git```

### 4. Cambiar al directorio yaru y compilar

```#cd yaru```

```#meson build```

```#cd build```

```#ninja install```

