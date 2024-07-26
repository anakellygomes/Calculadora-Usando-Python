---
editor_options: 
  markdown: 
    wrap: 72
---

```{python}
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "##Projeto Calculadora\n"
      ],
      "metadata": {
        "id": "CiWOEIVxHcnK"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "número= input( 'digite o número')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zFqNSZzrHj4v",
        "outputId": "ceb3ef3a-eff7-4fd2-d317-31317763bf26"
      },
      "execution_count": 5,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "digite o número  0, 1, 2, 3, 4\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "num= '0'\n",
        "num_convert= int(num)\n",
        "print ('num_convert', type (num_convert))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "GczrtwWlKPBZ",
        "outputId": "367240ad-4378-4384-8363-b7d44cee9872"
      },
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_convert <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "num= '1'\n",
        "num_convert= int(num)\n",
        "print ('num_convert', type (num_convert))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZZWxcYUqQVa3",
        "outputId": "9317dfa7-dd37-4e24-ef4c-0a5656754160"
      },
      "execution_count": 24,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_convert <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "num= '2'\n",
        "num_convert= int(num)\n",
        "print ('num_convert', type (num_convert))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uvI9GJteQX8l",
        "outputId": "e95a387c-f6dc-415c-ed01-25edc89b9eaf"
      },
      "execution_count": 27,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_convert <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "num= '3'\n",
        "num_convert= int(num)\n",
        "print ('num_convert', type (num_convert))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "1cIHH6BhQdFg",
        "outputId": "63ef02cc-8d35-45ad-cdaf-590224e60ca1"
      },
      "execution_count": 29,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_convert <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "num= '4'\n",
        "num_convert= int(num)\n",
        "print ('num_convert', type (num_convert))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "VgTyHgWiQf2a",
        "outputId": "ed4b8551-588e-4010-a77d-f97545e23365"
      },
      "execution_count": 31,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_convert <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#float\n",
        "num_float= float (num)\n",
        "print('num_float', num_float)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "pwst-SO0OhwG",
        "outputId": "f95d9a0d-8efa-41e6-f456-f1fb08f5eef2"
      },
      "execution_count": 18,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_float 0.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#float\n",
        "num_float= float (num)\n",
        "print('num_float', num_float)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8ZlQoTcVQk2D",
        "outputId": "f2724a68-5114-49a2-f605-2387e1ca03d0"
      },
      "execution_count": 25,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_float 1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#float\n",
        "num_float= float (num)\n",
        "print('num_float', num_float)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "HBZ3vJcCQssU",
        "outputId": "464415cd-8eeb-422f-e34a-feacdd506301"
      },
      "execution_count": 28,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_float 2.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#float\n",
        "num_float= float (num)\n",
        "print('num_float', num_float)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "yz9E2qjAQ1Jq",
        "outputId": "15bbaa26-3902-4919-c889-24d2a2bf82bf"
      },
      "execution_count": 30,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_float 3.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#float\n",
        "num_float= float (num)\n",
        "print('num_float', num_float)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kKGESzPQQ6fi",
        "outputId": "72e13e38-01b2-404c-8842-d22ab66c4d8a"
      },
      "execution_count": 32,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "num_float 4.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#for range\n",
        "for contador in range(40):\n",
        "  print(contador)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0r4xQoAUWVEP",
        "outputId": "c42e17ec-0917-4e3e-ad06-3a636c17115f"
      },
      "execution_count": 48,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n",
            "11\n",
            "12\n",
            "13\n",
            "14\n",
            "15\n",
            "16\n",
            "17\n",
            "18\n",
            "19\n",
            "20\n",
            "21\n",
            "22\n",
            "23\n",
            "24\n",
            "25\n",
            "26\n",
            "27\n",
            "28\n",
            "29\n",
            "30\n",
            "31\n",
            "32\n",
            "33\n",
            "34\n",
            "35\n",
            "36\n",
            "37\n",
            "38\n",
            "39\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#break\n",
        "for contador in range(100):\n",
        "  print(contador)\n",
        "  if contador ==40:\n",
        "    break"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "collapsed": true,
        "id": "uyCkm6c4ZmOq",
        "outputId": "cfdb98f7-1708-46c0-98e6-cb8b1518a779"
      },
      "execution_count": 49,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n",
            "11\n",
            "12\n",
            "13\n",
            "14\n",
            "15\n",
            "16\n",
            "17\n",
            "18\n",
            "19\n",
            "20\n",
            "21\n",
            "22\n",
            "23\n",
            "24\n",
            "25\n",
            "26\n",
            "27\n",
            "28\n",
            "29\n",
            "30\n",
            "31\n",
            "32\n",
            "33\n",
            "34\n",
            "35\n",
            "36\n",
            "37\n",
            "38\n",
            "39\n",
            "40\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#for com operadores compostos\n",
        "\n",
        "lista2 = [0,1,2, 3, 4]\n",
        "for val in lista2:\n",
        "  val+= 1\n",
        "  print(val)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_GPN9KT2aSC-",
        "outputId": "9f2ff4cf-ee64-4b8c-e2a1-74c818e588e1"
      },
      "execution_count": 41,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "\n",
        "lista2 = [0,1,2, 3, 4]\n",
        "for val in lista2:\n",
        "  val-= 1\n",
        "  print(val)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "cE40Izt7aWfR",
        "outputId": "9cb89e8a-090f-4918-97c8-c557653c6f2f"
      },
      "execution_count": 42,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "-1\n",
            "0\n",
            "1\n",
            "2\n",
            "3\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "\n",
        "lista2 = [0,1,2, 3, 4]\n",
        "for val in lista2:\n",
        "  val*= 2\n",
        "  print(val)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "EB89QikUacg6",
        "outputId": "cb3f8897-5414-4527-da62-8096723d2bcd"
      },
      "execution_count": 43,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "2\n",
            "4\n",
            "6\n",
            "8\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "\n",
        "lista2 = [0,1,2, 3, 4]\n",
        "for val in lista2:\n",
        "  val/= 2\n",
        "  print(val)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "jVJHHihUahzm",
        "outputId": "9da40c16-8c6e-4e02-b809-6b1dfef2ee4f"
      },
      "execution_count": 46,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0.0\n",
            "0.5\n",
            "1.0\n",
            "1.5\n",
            "2.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#for com operadores compostos\n",
        "\n",
        "lista2 = [0,1,2, 3, 4]\n",
        "for val in lista2:\n",
        "  val%= 4\n",
        "  print(val)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "O5n9XebFbCzi",
        "outputId": "0cf91b3d-3f20-41a5-ff89-92de8d7f0f47"
      },
      "execution_count": 50,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "1\n",
            "2\n",
            "3\n",
            "0\n"
          ]
        }
      ]
    }
  ]
}
```

op= '' while op != 's' : op = input('''Qual a opção desejada? Escolha
dentre as seguintes opções:'+' para soma '/' para divisão '-' para
subtração '\*' para multiplicação 's' para sair/encerrar o programa

```         
 Operação = ''')
```

try: n1= int(input('1 número:')) n2= int(input('2 número:'))

except: print('Entrar com números inteiros!')

else: if op == '+' : print(f'{n1} + {n2} = {n1 + n2}')

elif op == '-' : print (f' {n1} - {n2} = {n1 - n2} ')

elif op == '*' : print (f' {n1}* {n2} = {n1 \* n2}')

else : try: print(f' {n1} / {n2} = {n1 / n2} ')

except : print( 'divisão por zero não permitido!')
print('..................\n')

print(' Programa finalizado!')
