# Bash Scripts (J.)

## How to

It's better to make those scripts executable with `chmod +x [ SCRIPT ]` and then execute them like that:

```
./[ SCRIPT ]
```

Alternatively, you may use:

```
bash [ SCRIPT ]
```

Here are additional instructions for specific scripts:

### ProcDDoS

```
sudo su
./procddos
```

### FileCleaner

```
./filecleaner [ FILE_1 ] [ FILE_2 ] [ FILE_n ]
Alternatively, you can pass wildcards:

./filecleaner *.jpg
```
