# Aula-5
using System;

  //Repositório referente a primeira aula C#.
class Program {
  public static void Main (string[] args) {
    int num;
    Console.WriteLine("Digite um número");
    num = int.Parse(Console.ReadLine());

      if(num >= 0) {
        Console.WriteLine("Número positivo");
      }
      else{
        Console.WriteLine("Número negativo");
      }
  }
}
