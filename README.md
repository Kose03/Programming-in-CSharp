# Programming-in-CSharp
    addMe :: Integer -> Integer -> Integer
    addMe x y = x + y
    main :: IO ()
    main =  do
    strInputOne <- getLine
    strInputTwo <- getLine
    let inputOne = read strInputOne :: Integer
    let inputTwo = read strInputTwo :: Integer
    let text = "Sum of x + y = " ++ show (addMe inputOne inputTwo)
    writeFile "myFile.txt" text
    fileText <- readFile "myFile.txt"
    putStr fileText





Нова програма


    readI x = read x:: Integer

    main = do
    input <- getLine
    let x = readI input
    input <- getLine
    let y = readI input
    print(x + y)
    
   
