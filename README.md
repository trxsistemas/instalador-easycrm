DESCARGANDO EL INSTALADOR E INICIANDO LA PRIMERA INSTALACIÓN (USAR SOLO PARA LA PRIMERA INSTALACIÓN):

```bash
sudo apt install -y git && git clone https://github.com/plwdesign/instalador-easycrm && sudo chmod -R 777 instalador-easycrm && cd instalador-easycrm && sudo ./install_primaria
```

ACCEDIENDO AL DIRECTORIO DEL INSTALADOR E INICIANDO INSTALACIONES ADICIONALES (USAR ESTE COMANDO PARA SEGUNDA O MÁS INSTALACIÓN):
```bash
cd ./instalador-easycrm && sudo ./install_instancia
```

