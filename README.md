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
