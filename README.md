- 👋 Hi, I’m @sara-tho
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sara-tho/sara-tho is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

body {
   background-image: linear-gradient(-45deg, #8067B7, #EC87C0);
   min-height: calc(100vh - 40px);
   margin: 20px;
   font-family: 'Lato', sans-serif;
   widget {
      filter: drop-shadow(1px 1px 3px rgba(0, 0, 0, 0.3));
      &[type="ticket"] {
         width: 255px;
         .top,
         .bottom {
            >div {
               padding: 0 18px;
               &:first-child {
                  padding-top: 18px;
               }
               &:last-child {
                  padding-bottom: 18px;
               }
            }
            img {
               padding: 18px 0;
            }
         }
         .top,
         .bottom,
         .rip {
            background-color: #fff;
         }
         .top {
            border-top-right-radius: 5px;
            border-top-left-radius: 5px;
            .deetz {
               padding-bottom: 10px !important;
            }
         }
         .bottom {
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
            padding: 18px;
            height: 30px;
            padding-top: 10px;
            .barcode {
               background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAF4AAAABCAYAAABXChlMAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAYdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuOWwzfk4AAACPSURBVChTXVAJDsMgDOsrVpELiqb+/4c0DgStQ7JMYogNh2gdvg5VfXFCRIZaC6BOtnoNFpvaumNmwb/71Frrm8XvgYkker1/g9WzMOsohaOGNziRs5inDsAn8yEPengTapJ5bmdZ2Yv7VvfPN6AH2NJx7nOWPTf1/78hoqgxhzw3ZqYG1Dr/9ur3y8vMxgNZhcAUnR4xKgAAAABJRU5ErkJggg==);
               background-repeat: repeat-y;
               min-width: 58px;
            }
            .buy {
               display: block;
               font-size: 12px;
               font-weight: bold;
               background-color: #5D9CEC;
               padding: 0 18px;
               line-height: 30px;
               border-radius: 15px;
               color: #fff;
               text-decoration: none;
            }
         }
         .rip {
            height: 20px;
            margin: 0 10px;
            background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAYAAAACCAYAAAB7Xa1eAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAYdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuOWwzfk4AAAAaSURBVBhXY5g7f97/2XPn/AcCBmSMQ+I/AwB2eyNBlrqzUQAAAABJRU5ErkJggg==);
            background-size: 4px 2px;
            background-repeat: repeat-x;
            background-position: center;
            position: relative;
            box-shadow: 0 1px 0 0 #fff, 0 -1px 0 0 #fff;
            &:before,
            &:after {
               content: '';
               position: absolute;
               width: 20px;
               height: 20px;
               top: 50%;
               transform: translate(-50%, -50%) rotate(45deg);
               border: 5px solid transparent;
               border-top-color: #fff;
               border-right-color: #fff;
               border-radius: 100%;
               pointer-events:none;
            }
            &:before {
               left: -10px;
            }
            &:after {
               transform: translate(-50%, -50%) rotate(225deg);
               right: -40px;
            }
         }
      }
      .-bold {
         font-weight: bold;
      }
   }
}


