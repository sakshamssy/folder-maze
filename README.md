# folder-maze

Teach kids directory structure and terminal.

Use the `cd` command to navigate the folder maze, find `treasure.txt`, and `cat` to open the treasure box.

## Generate Folder Maze

```bash
$ ./make.sh -n 40 -w 10
```

## See the Map

```bash
$ tree ./start
start/
└── home
    └── catkin_ws
        ├── exclu
        │   ├── 09
        │   │   ├── 00
        │   │   └── 24
        │   │       ├── 11
        │   │       │   └── 20
        │   │       │       ├── 17
        │   │       │       │   ├── 08
        │   │       │       │   │   ├── 03
        │   │       │       │   │   │   ├── 25
        │   │       │       │   │   │   └── 31
        │   │       │       │   │   └── 27
        │   │       │       │   │       └── 23
        │   │       │       │   │           └── 04--keep_trying.txt(monkey)
        │   │       │       │   ├── 30
        │   │       │       │   └── 34
        │   │       │       │       └── 19
        │   │       │       └── 26
        │   │       │           └── 12--go_back_a_bit.txt
        │   │       └── 16
        │   └── 22
        │       ├── 35
        │       │   ├── 21
        │       │   │   └── 05
        │       │   │       └── 07
        │       │   │           └── 18
        │       │   │               ├── 10
        │       │   │               │   ├── 14
        │       │   │               │   │   └── 15
        │       │   │               │   │       └── 13--SideQuest.txt(rhino)
        │       │   │               │   └── treasure----treasure.txt(FinalDestination(PolarBear)
        │       │   │               └── 28--as_close_u_can_get.txt(camel)
        │       │   ├── 32
        │       │   └── 33
        │       └── 37
        └── inclu
            ├── f45
            └── arc_folder
                └── not_what_u_want.txt
```

## Make Cool Treasure

ASCII Art Generator
- http://patorjk.com/software/taag/#p=display&f=Sub-Zero&t=Type%0ASomething

ASCII Zoo Animals
- http://www.geocities.ws/SoHo/7373/zoo.html
