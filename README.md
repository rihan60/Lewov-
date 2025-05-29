import { useEffect } from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";
import { motion } from "framer-motion";

const products = [
  {
    name: "Drop Shoulder Hoodie",
    description: "Premium cotton drop shoulder hoodie with Lewov branding.",
    price: "$45",
    img: "https://images.unsplash.com/photo-1602810316533-6f5bb18d96b3?auto=format&fit=crop&w=500&q=80"
  },
  {
    name: "Streetwear Tee",
    description: "Oversized T-shirt with subtle Lewov sleeve print.",
    price: "$30",
    img: "https://images.unsplash.com/photo-1552374196-c4e7ffc6e126?auto=format&fit=crop&w=500&q=80"
  },
  {
    name: "Cargo Pants",
    description: "Stylish and comfortable utility pants for all day wear.",
    price: "$50",
    img: "https://images.unsplash.com/photo-1580983561447-7b6f4b3e5d17?auto=format&fit=crop&w=500&q=80"
  }
];

export default function LewovStore() {
  useEffect(() => {
    document.body.style.backgroundColor = "#f5e1c0";
  }, []);

  return (
    <div className="min-h-screen px-4 py-8">
      <motion.h1
        className="text-4xl font-bold text-center mb-10"
        initial={{ opacity: 0, y: -40 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8 }}
      >
        Lewov Clothing Store
      </motion.h1>

      <motion.div
        className="grid grid-cols-1 md:grid-cols-3 gap-6 mb-16"
        initial="hidden"
        animate="visible"
        variants={{
          hidden: { opacity: 0 },
          visible: {
            opacity: 1,
            transition: {
              delayChildren: 0.3,
              staggerChildren: 0.2
            }
          }
        }}
      >
        {products.map((product, index) => (
          <motion.div
            key={index}
            className="hover:scale-105 transition-transform"
            whileHover={{ scale: 1.05 }}
          >
            <Card className="rounded-2xl shadow-xl">
              <img
                src={product.img}
                alt={product.name}
                className="rounded-t-2xl w-full h-60 object-cover"
              />
              <CardContent className="p-4">
                <h2 className="text-xl font-semibold mb-1">{product.name}</h2>
                <p className="text-sm text-gray-700 mb-2">{product.description}</p>
                <p className="font-bold text-lg">{product.price}</p>
              </CardContent>
            </Card>
          </motion.div>
        ))}
      </motion.div>

      <motion.div
        className="bg-white rounded-2xl p-6 shadow-lg max-w-2xl mx-auto"
        initial={{ opacity: 0, y: 50 }}
        whileInView={{ opacity: 1, y: 0 }}
        viewport={{ once: true }}
        transition={{ duration: 0.6 }}
      >
        <h3 className="text-2xl font-bold mb-4 text-center">Contact Us</h3>
        <form className="space-y-4">
          <Input placeholder="Your Name" required />
          <Input type="email" placeholder="Your Email" required />
          <Textarea placeholder="Message" rows={4} required />
          <div className="text-center">
            <Button className="bg-black text-white rounded-xl px-6 py-2 hover:bg-gray-800">
              Send Message
            </Button>
          </div>
        </form>
      </motion.div>
    </div>
  );
}
