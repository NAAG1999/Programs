## Connecting with different databases

### Oracle Database

Driver class = oracle.driver.OracleDriver
Connection url = jdbc:oracle:this@localhost:Port_number:xe

Ex:-
```java
import java.sql.*;

class sql1{
	public static void main(String ar[]){
		try {
			Class.forName("oracle:driver:OracleDriver"; "UserName"; "Password");
			Connection con = DriverManager.getConnection(url);
			Statement stmt = con.createStatement();
			}
	}
}
```