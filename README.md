

    ABC College Library Board website
    
        body {
            color: black;
        }
        
        h1 {
            color: purple;
            text-align: center;
            font-weight: bold;
        }
        
        .box {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
        }
        
        .box-title {
            color: blue;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .announcements li {
            list-style-type: disc;
            margin-left: 20px;
        }
        
        table {
            margin: 0 auto;
            border-collapse: collapse;
        }
        
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        
        .picture {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .picture-title {
            font-weight: bold;
        }
        
        .contact {
            margin-bottom: 20px;
        }
        
        .contact-title {
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .copyright {
            color: red;
            text-align: center;
        }
    


    # ABC College Library Board website
    
    
        ABC College Library
            xxx
    
    
    
        Announcements
        <ul class="announcements">
            * xxx
            * xxx
            * xxx
        
    
    
    
        Rules
        
            
                DOs
                DON'Ts
            
            
                xxx
                xxx
            
            
                xxx
                xxx
            
            
                xxx
                xxx
            
            
                xxx
                xxx
            
        
    
    
    
        粵語審音配詞字庫
        [
            
        ](https://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/)
    
    
    
        Contact
        <ol class="contact">
            1. xxx
            1. xxx
            1. xxx
        
    
    
    
        Copyright &copy; 2023, ABC College Library Board. All rights reserved.
    

converter := md.NewConverter("", true, nil)

html = `<strong>Important</strong>`

markdown, err := converter.ConvertString(html)
if err != nil {
  log.Fatal(err)
}
fmt.Println("md ->", markdown)
