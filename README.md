<h1>HW1</h1>


```swift


import SwiftUI

struct ContentView: View {
    var body: some View {
        HStack{
            ZStack{
                    Image("Bg")
                        .resizable()
                        .aspectRatio(contentMode: /*@START_MENU_TOKEN@*/.fill/*@END_MENU_TOKEN@*/)
                        .frame(width: 500, height: 500, alignment: .leading)
                        
                    Text("1101525     許鋮昱")
                        .font(.system(size: 45, weight: .bold))
                        .frame(width: 400, height: 100, alignment: .center)
                        .foregroundColor(.black)
                        .offset(x: 0, y: -150)
                    Image(systemName: "music.mic")
                        .font(.system(size: 60, weight: .bold))
                        .offset(x: 0, y: -12.5)
                        .foregroundColor(Color.black)
                Text("\"Less  is  more\"")
                    .font(.system(size: 45, weight: .bold))
                    .frame(width: 400, height: 100, alignment: .center)
                    .foregroundColor(.black)
                    .offset(x: 0, y: 125)
            }
            Image("Jeff1")
                .resizable()
                .aspectRatio(contentMode: /*@START_MENU_TOKEN@*/.fill/*@END_MENU_TOKEN@*/)
                .frame(width: 500, height: 500, alignment: .trailing)
        } 
    }
}
```
![CFCA1FC5-F882-4C0E-96A2-5C830AD27CE5](https://github.com/Jefffffrey/HW1/assets/125536328/ac86ec73-20fb-4b84-a8b7-35e06ba9fd32)
