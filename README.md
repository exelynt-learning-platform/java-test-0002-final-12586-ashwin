# java-test-0002-final-12586-ashwin
Final Project Assignment - This repository contains the complete final project code and documentation.

class JavaAssignment002
{
  public static void main(String[]args)
    {
        int n = 5;

        for(int i = 1 ; i <= n ; i++)
          {
              for(int j = 1 ; j <= n - i ; j++)
                {
                    System.out.print("  ");
                }

                for(int s = 1 ; s <= i ; s++)
                  {
                      System.out.print(s + " ");
                  }

                  for(int j = i -1 ; j >= 1 ; j--)
                    {
                        System.out.print(j + " ");
                    }

                    System.out.println();
          }
    }
}
