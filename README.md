# CHESSAI

A chess game written in Java with a built in AI to play against.

About CHESSAI:
- Uses Guava for Immutability to protect board state
- Uses Swing for its GUI
- 4 different chess pieces styles easily accessible in menubar
- Able to choose board dark and light color tiles
- Option to save and load game in FEN or PGN format
- Option to choose AI depth level (difficulty)
- Highlight available moves

## AI Focus
- Alpha Beta move ordering
- Iterative Deepening
- Mini Max
- Stock Alpha Beta

All these are simple implementations of the larger algoritms and not the most efficient.
The move ordering and Stock algo help make our MiniMax program be more efficient but can be improved.

## Getting Started

### Pre-Requisites
Written in Java 17.

Uses a Guave external library which comes with the project so no need to find your own.

### Installation

Clone the repo

``` sh
git clone https://github.com/cherlesmd/ChessAI.git
```

Run in your preffered IDE or run the following commands
``` sh
javac -d bin -cp "lib/guava-18.0.jar" src/com/chess/*.java
```
``` sh
java -cp "bin:lib/guava-18.0.jar" com.chess.Chess  
```

## Contributing

If you would like to fully flesh out this game or take it a different direction you are welcome to contribute or fork your own to work on.

If you want to directly contribute to this repo

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/YourFeature)
3. Commit your Changes (git commit -m 'Add some YourFeature')
4. Push to the Branch (git push origin feature/YourFeature)
5. Open a Pull Request

## License

Distributed under the MIT License. See LICENSE.txt for more information.
