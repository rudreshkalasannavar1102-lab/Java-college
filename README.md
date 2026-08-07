# Java-college
Only for college purpose
class Bank
{
    String Name;
    int Accno;
    int IFSCcode;
    Bank(String Name,int Accno,int IFSCcode){
        this.Name=Name;
        this.Accno=Accno;
        this.IFSCcode=IFSCcode;
    }
    void display(){
            System.out.println(Name+" "+Accno+" "+IFSCcode);
    }
    public static void main(String[]args){
                Bank b1=new Bank("Raj",325216,216);
                b1.display();
    }
}
      
