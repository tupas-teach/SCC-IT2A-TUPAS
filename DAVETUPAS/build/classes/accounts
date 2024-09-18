
public class ACCOUNT {
   private int id;
   private String FirstName;
   private String LastName;
   private String email;
   private String username;
   private String password;
   
   public void  Account(int id, String FirstName , String LastName, String email, String username, String password){
       this.id = id;
       this.FirstName = FirstName;
       this.LastName = LastName;
       this.email = email;
       this.username = username;
       this.password = password;
       
   }
   public int getid(){
       return id;
   }
    public  String getfirstName(){
        return FirstName;
    }
    public String getlastname(){
        return LastName;
    }
    public String getemail(){
        return email;
    }
    public String getusername(){
        return username;
    }
    public String getpassword(){
        return password;
    }
    public void setPassword(String password){
       // validate Password(password);
        
    }
    public void validatePassword(String password){
        // Password validation criteria
        if (password.length()< 8){
            System.out.println("Error: Password must be at least 8 Character long :");
                 return;   
        }
        if(! password.matches("[a-z")){
            System.out.println("Error: Password must be at least one uppercase and one lowercase letter:");
            return;
        
        }
        if(!password.matches("\\ d")){
            System.out.println("Error: must be at least one number:");
            return;
        }
            if(password.matches("[!@#$%^*]")){
                System.out.println("Error: Passwordmust be at lest special character");
                return;
            }
            if(password.matches("admin")) || password.matches("password") || password.matches("1234")){
                System.out.println("");
            }
        }
    }
    
    
    
