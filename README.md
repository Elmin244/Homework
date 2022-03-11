# Homework
using System;

namespace homework0311
{
    class Program
    {
        static void Main(string[] args)
        {
            Product product = new Product();
            product.Name = "Qelem";
            product.BrandName = "Yazi yazmaq ucun";
            product.Price=20;
        } 
    }
    class Product
    {
        public string Name;
        public string BrandName;
        public int Price;
    }
}
namespace homework2
{
    class Program
    {
        static void Main(string[] args)
        {
            Vehicle vehicle = new Vehicle();
            Car car = new Car();
            car.Color = "yellow";
            car.Name = "Audi";
        }
    }
    class Vehicle
    {
        public string Color;
        public string Name;
    }
    class Car :Vehicle
    {
        public string Brand;
        public string Model;
    }
}
