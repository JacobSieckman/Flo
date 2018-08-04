# Flo
A wonderful project I followed along with by Andriy Kharchyshyn (https://www.raywenderlich.com/162315/core-graphics-tutorial-part-1-getting-started). Update note: This tutorial has been updated to iOS 11, Swift 4, and Xcode 9 by Andrew Kharchyshyn. The original tutorial was written by Caroline Begbie.

Although it has been updated for iOS 11, Swift 4, and Xcode 9 I am running iPhone 7 in the simulator, Swift 3.1, and Xcode 8.2.1 (8C1002). Everything works with the exception of NSAttributedStringKey. Since Swift 4 has made some updates to strings, NSAttributedStringKey - as declared in Kharchyshyn's tutorial - gets errors.

The error is located at MedalView.swift -> 

/*let numberOne = "1" as NSString
        let numberOneRect = CGRect(x: 47, y: 100, width: 50, height: 50)
        let font = UIFont(name: "Academy Engraved LET", size: 60)!
        let numberOneAttributes = [
            NSAttributedStringKey.font: font,
            NSAttributedStringKey.foregroundColor: darkGoldColor
        ]
        numberOne.draw(in: numberOneRect, withAttributes: numberOneAttributes)*/
        
        
