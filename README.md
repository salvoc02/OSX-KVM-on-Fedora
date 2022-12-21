# OSX-KVM
Come installare MacOS su una macchina virtuale, da linux

PS: questa guida è stata testata su fedora, quindi alcuni comandi da terminale e alcuni nomi dei pacchetti potrebbero variare se state usando un'altra versione di linux.

# Installare il necessario:

Librerie:
```
$ sudo dnf install virt-manager
$ sudo dnf install libvirt-daemon qemu qemu-img python3 python3-pip git
```

Abilitare libvirt:
```
$ sudo systemctl enable libvirtd
$ sudo systemctl enable libvirtd
```

File necessari:
```
$ git clone https://github.com/foxlet/macOS-Simple-KVM.git
$ git clone https://github.com/corpnewt/gibMacOS.git
```

# Scaricare immagine macos


```
$ cd gibMacOS
