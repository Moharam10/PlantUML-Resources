# PlantUML-Resources
- This is to host puml files that i need in my work
- image should not be transparent, otherwise this will not work

# do it for all the files inside folder /image/
```bash
./create_sprites.sh -p ./image/ xl 
```
# for working with svg 
```bash
./create_sprites.sh -s -p ./svg/ xl 
```

```bash
`java -jar plantuml.jar -encodesprite 16z foo.png`
```
