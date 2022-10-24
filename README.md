# basic_swift


import UIKit

var greeting = "Hello, playground"

/*
 옵셔널
 12라는 string은 Int로 형변환
 ? 
*/
let string = "12"
var stringToInt: Int! = Int(string)
//var stringToInt: Int? = Int(string)
print(stringToInt + 1)

/*
    형변환시 AA를 int로 바꿔주는경우 nil이 발생
    옵셔널 해제 = !
    이미 nil값이므로 옵셔널해제가 의미가 없음
*/
let string2 = "AA"
var stringToInt2: Int! = Int(string2)
//print(stringToInt2 + 1)



