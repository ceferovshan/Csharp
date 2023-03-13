//string username = "kullanici_adi"; //Giri icin code
//string password = "sifre";

//string enteredUsername;
//string enteredPassword;

//while (true)
//{
//    Console.Write("Kullanıcı adınızı girin: ");
//    enteredUsername = Console.ReadLine();

//    Console.Write("Şifrenizi girin: ");
//    enteredPassword = Console.ReadLine();

//    if (enteredUsername == username && enteredPassword == password)
//    {
//        Console.WriteLine("Giriş başarılı.");
//        break;
//    }
//    else
//    {
//        Console.WriteLine("Kullanıcı adı veya şifre yanlış. Tekrar deneyin.");
//    }
//}

//Console.ReadLine();

//Console.Write("Ededi daxil edin : "); //reqemin toplanmasi
//long a = Convert.ToInt32(Console.ReadLine());
//int total = 0;
//for (int z = 0; z <= a; z++)
//{
//    total += z;
//}
//Console.WriteLine(total);
//Console.Read();

//Console.Write("Ededi daxil edin :"); // Faktorial
//int a = Convert.ToInt32(Console.ReadLine());
//int total = 1;
//for (int i = 1; i <= a; i++)
//{
//    total *= i;
//}
//Console.WriteLine(total);

//Console.WriteLine("Ededi daxil edin : ");// ededlerin vurulmasi (* bunsuz)
//int a = Convert.ToInt32(Console.ReadLine());
//Console.WriteLine("ikinci Ededi daxil edin : ");
//int b = Convert.ToInt32(Console.ReadLine());
//int total = 0;
//for (int i = 0; i < a; i++)
//{
//    total += b;
//}
//Console.WriteLine(total);

//Console.WriteLine("Ededi daxil edin : "); //sade ve mut=rekkeb ededler
//int a = Convert.ToInt32(Console.ReadLine());
//int c = 0;
//for (int i = 2; i < a; i++)
//{
//    if (a % i == 0)
//    {
//        c += 1;
//        Console.WriteLine(c + " " + a + " " + i);
//    }
//}
//if (c > 0)
//{
//    Console.WriteLine(" murekkeb ededdir");
//    Console.WriteLine(c + " " + a);
//}
//if (c == 0)
//{
//    Console.WriteLine(" sade ededdir");
//    Console.WriteLine(c + " " + a);
//}

//Console.WriteLine("Ededi daxil edin : "); /ADV qiymeti
//int deyer = Convert.ToInt32(Console.ReadLine());
//int ADV_deyer = deyer + (deyer * 18) / 100;
//Console.WriteLine(ADV_deyer + " ADV'li qiymeti");

//int[] a = { 5, 8, 6, 7, 8 }; //ARRAY
//Console.WriteLine(a[2]);

//class Program //En boyuk reqemi tapmaq ucun
//{
//    static void Main(string[] args)
//    {
//        int[] sayilar = new int[] { 360, 47, 59, 78, 55, 102, 305 };

//        int enBuyukSayi = sayilar[0];

//        for (int i = 1; i < sayilar.Length; i++)
//        {
//            if (sayilar[i] > enBuyukSayi)
//            {
//                enBuyukSayi = sayilar[i];
//            }
//        }

//        Console.WriteLine("En büyük sayı: " + enBuyukSayi);
//        Console.ReadLine();
//    }
//}


