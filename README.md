# SIMETBox Config

Biblioteca para ler configuração do SIMETBox

## Instalação

No caso do uso do [SIMETBox Feed](https://github.com/simetnicbr/simetbox-openwrt-feed.git), para os projetos OpenWRT e LEDE, esta biblioteca é baixada e usada de forma automática. Caso se queira compilar o projeto [simetbox-openwrt-base](https://github.com/simetnicbr/simetbox-openwrt-feed.git) deve-se compilar este projeto separadamente:

```bash
git clone https://github.com/simetnicbr/simetbox-openwrt-base.git
cd simetbox-openwrt-base
autoreconf
automake --add-missing
./configure
make install
```

## Uso

É usado pelo projeto simetbox-openwrt-base

## History

2015-05-23 - Primeiro release

## Credits

NIC.br  
<medicoes@simet.nic.br>

## License

GPL-2