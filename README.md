# hellovapor

sampling swift on server side

## tested environment

- fedora 40

## requirements

- swift
- vapor toolbox

## provisioning

some of these commands will ask for sudo so pay attention to it.

```bash
sudo dnf install swift-lang
git clone https://github.com/vapor/toolbox.git
cd toolbox
git checkout 18.7.5
make install
cd ..
vapor new hellovapor -n
cd hellovapor
# fix // swift-tools-version in Package.swift if needed
swift run
# wit for the build then visit http://127.0.0.1:8080/hello 
```
