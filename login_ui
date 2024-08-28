import 'package:flutter/material.dart';

void main() {
  runApp(
    const Loginapp(),
  );
}

class Loginapp extends StatelessWidget {
  const Loginapp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        backgroundColor: Colors.white,
        body: SafeArea(
          child: SingleChildScrollView(
            child: Column(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
              children: [
                const SizedBox(height: 20),
                const Row(
                  mainAxisAlignment: MainAxisAlignment.center,
                  children: [
                    Image(
                        height: 70,
                        width: 100,
                        image: AssetImage(
                          'assets/king.jpg',
                        )),
                    SizedBox(width: 12),
                    Column(
                      crossAxisAlignment: CrossAxisAlignment.start,
                      children: [
                        Text(
                          "Linuxx",
                          style: TextStyle(
                            fontSize: 35,
                            fontFamily: 'Rubik Meduim',
                          ),
                        ),
                        Text(
                          "DUCK",
                          style: TextStyle(
                              fontSize: 35,
                              fontFamily: 'Rubik Meduim',
                              color: Colors.deepOrange),
                        ),
                      ],
                    )
                  ],
                ),
                const SizedBox(height: 50),
                const Center(
                    child: Text(
                  "Login",
                  style: TextStyle(
                      fontFamily: 'Rubik Meduim',
                      fontSize: 25,
                      color: Colors.black87),
                )),
                const SizedBox(height: 15),
                const Center(
                  child: Text(
                    "Thank you for watching my \nchannel do give feedback .",
                    textAlign: TextAlign.center,
                    style: TextStyle(
                        fontFamily: 'Rubik Regular',
                        color: Color(0xff4C5988),
                        fontSize: 16),
                  ),
                ),
                const SizedBox(height: 60),
                TextFormField(
                    decoration:  InputDecoration(
                        hintText: 'Email',
                        hintStyle: const TextStyle(fontFamily: 'Rubik Regular'),
                        fillColor: const Color(0xffF8F9FA),
                        filled: true,
                        prefixIcon:
                          const  Icon(Icons.email_rounded, color: Colors.deepOrange),
                      focusedBorder: OutlineInputBorder(
                        borderSide: const BorderSide(color: Color(0xffE4E7EB)), // Named parameter
                        borderRadius: BorderRadius.circular(45), // Named parameter
                      ),
                      enabledBorder: OutlineInputBorder(
                          borderSide:const BorderSide(color: Color(0xffE4E7EB)),
                          borderRadius:BorderRadius.circular(15)
                      ),
                    ),
                ),
                 const  SizedBox(height:20),
            
                TextFormField(
                  decoration:  InputDecoration(
                    hintText: 'Password',
                    hintStyle: const TextStyle(fontFamily: 'Rubik Regular'),
                    fillColor: const Color(0xffF8F9FA),
                    filled: true,
                    prefixIcon:
                    const  Icon(Icons.lock_rounded, color: Colors.deepOrange),
                    focusedBorder: OutlineInputBorder(
                  borderSide: const BorderSide(color: Color(0xffE4E7EB)), // Named parameter
            borderRadius: BorderRadius.circular(45), // Named parameter
                    ),
                    enabledBorder: OutlineInputBorder(
                        borderSide:const BorderSide(color: Color(0xffE4E7EB)),
                        borderRadius:BorderRadius.circular(15)
                  ),
            
                ),
            
                ),
                const SizedBox(height: 300,),
            
                Container(
                  decoration: BoxDecoration(
                    borderRadius: BorderRadius.circular(25),
                    color: Colors.deepOrange,
                  ),
                  height: 50,
                  width: 200,
                  child: const Center(
                      child: Text(
                    "Log In",
                    style: TextStyle(
                        fontSize: 15,
                        fontFamily: 'Rubik Meduim',
                        color: Colors.white),
                  )),
                ),
                const SizedBox(height: 20),
                const Row(
                  mainAxisAlignment: MainAxisAlignment.center,
                  children: [
                    Text(
                      "Don't have a acoount? ",
                      style: TextStyle(
                          fontSize: 15,
                          fontFamily: 'Rubik Regular',
                          color: Color(0xff4C5988)),
                    ),
                    Text(
                      "SIGN UP",
                      style: TextStyle(
                        fontSize: 15,
                        fontFamily: 'Rubik Meduim',
                        color: Colors.deepOrange,
                      ),
                    )
                  ],
                ),
            
              ],
            ),
          ),
        ),
      ),
    );
  }
}
