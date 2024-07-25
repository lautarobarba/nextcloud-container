# Nextcloud

## Reverse proxy
Si se usa detras de un reverse proxy hay que agregar la siguiente linea de configuracion para que funcionen los clientes de escritorio.
En nextcloud/config/config.php agregar:

'overwrite.cli.url' => 'http://nextcloud.lautarobarba.com.ar',
'overwriteprotocol' => 'https',

