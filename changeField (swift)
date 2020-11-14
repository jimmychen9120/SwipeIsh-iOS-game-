func changeField(coin: Int){
        lowerField.isUserInteractionEnabled = false
        upperField.isUserInteractionEnabled = false
        firstP1.isHidden = true
        firstP2.isHidden = true
        
        if coin == 0{
            lowerField.image = UIImage(named: "Red_Attacker")
            upperField.image = UIImage(named: "Blue_Defender")
            
            if userSettings.float(forKey: "Timer_Slider") == 0{
                gameP1()
            }else{
                startTimer(slider_Value: userSettings.float(forKey: "Timer_Slider"), coin: coin)
            }
        }else{
            lowerField.image = UIImage(named: "Blue_Defender")
            upperField.image = UIImage(named: "Red_Attacker")
            
            if userSettings.float(forKey: "Timer_Slider") == 0{
                gameP2()
            }else{
                startTimer(slider_Value: userSettings.float(forKey: "Timer_Slider"), coin: coin)
            }
        }
    }
