func startTimer(slider_Value: Float, coin: Int){
        let delay = Double(slider_Value/5)
        var i = 1
        timer = Timer.scheduledTimer(withTimeInterval: delay, repeats: true){(timer) in
            if i>4{
                timer.invalidate()
            }else{
                switch(i){
                case 1:
                    self.updateImages(UIImage(named: "P1Timer1"), UIImage(named: "P2Timer1"))
                case 2:
                    self.updateImages(UIImage(named: "P1Timer2"), UIImage(named: "P2Timer2"))
                case 3:
                    self.updateImages(UIImage(named: "Timer3"), UIImage(named: "Timer3"))
                case 4:
                    self.logo.image = UIImage(named: "Timer4_Logo")
                default:
                    self.updateImages(UIImage(named: "Timer0"), UIImage(named: "Timer0"))
                    self.logo.image = UIImage(named: "SwipeIsh_Logo")
                }

                i = i+1
            }
        }
}
