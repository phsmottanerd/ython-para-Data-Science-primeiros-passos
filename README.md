{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyPkEZNzZtJtuqvNeUIYUNch",
      "include_colab_link": true
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
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/phsmottanerd/-Proje-Emojis-Utilizando-Javascript/blob/main/Python_para_Data_Science_primeiros_passos.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kwGEYQp-5H2l",
        "outputId": "d2524718-92cb-4dd1-8d45-7a0d0507c5d9"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "5\n"
          ]
        }
      ],
      "source": [
        "idade = 5\n",
        "print(idade)\n"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "idade = 10\n",
        "print(idade)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "PiAsFaDu7Dm5",
        "outputId": "b68a8826-98fe-4760-a7b3-79463cccd5bd"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "10\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "idade = 15\n",
        "idade"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "OrUYXPj97UWN",
        "outputId": "935b3181-ef69-4b5f-a77b-67281763d8b2"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "15"
            ]
          },
          "metadata": {},
          "execution_count": 3
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nome = 'Gabriel'\n",
        "nome"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "AEnAKi307p7E",
        "outputId": "4a628ed7-537c-456a-eb86-283e667fcfa3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Gabriel'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 4
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "i = 5\n",
        "type(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "81w2yvKS-EoY",
        "outputId": "e7805fdc-acc9-4827-8d18-a2014f621518"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "int"
            ]
          },
          "metadata": {},
          "execution_count": 5
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "f =9.8\n",
        "type(f)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "nrMZ2Qj6AHP8",
        "outputId": "e152eb14-800f-4964-c713-34ce0bf8a07e"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "float"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "s ='mirra'\n",
        "type(s)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "AJBjE9UEAPK4",
        "outputId": "0ba66a9b-6ad6-4f36-f4a9-d19e4fe30580"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "str"
            ]
          },
          "metadata": {},
          "execution_count": 7
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "b = True\n",
        "type(b)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "pNdxuNUcAWWv",
        "outputId": "279fd03a-5353-482c-b66e-cfd0b1e202c4"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "bool"
            ]
          },
          "metadata": {},
          "execution_count": 8
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nome_aluno ='Fabricio Daniel'\n",
        "idade_aluno = 15\n",
        "media_aluno = 8.45\n",
        "situacao_aprovado = True\n",
        "print(f'''nome do aluno:', nome_aluno, 'idade do aluno:', idade_aluno, 'media do aluno:', media_aluno, 'aprovação:', situacao_aprovado''')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zJRF_epLAdN3",
        "outputId": "808641f2-694e-402a-9dce-76085a0abbb6"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "nome do aluno:', nome_aluno, 'idade do aluno:', idade_aluno, 'media do aluno:', media_aluno, 'aprovação:', situacao_aprovado\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "XwE_ynje0MS5"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "q_seguranca = 5\n",
        "s_seguranca = 3000\n",
        "\n",
        "q_docente = 16\n",
        "s_docente = 6000\n",
        "\n",
        "q_diretoria = 1\n",
        "s_diretoria = 12500\n"
      ],
      "metadata": {
        "id": "Hat_YrfxKJRz"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "total_empregados = q_seguranca + q_docente + q_diretoria\n",
        "total_empregados"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "LlWpTIo21_cH",
        "outputId": "2cc7e2ce-f510-452c-d1df-d02e3f76de97"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "22"
            ]
          },
          "metadata": {},
          "execution_count": 14
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "diferenca_salario = s_diretoria - s_seguranca\n",
        "diferenca_salario"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "rvT1XV2B4634",
        "outputId": "1dc3a32c-d07f-43d8-e741-c2e3f2f5cf9b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "9500"
            ]
          },
          "metadata": {},
          "execution_count": 29
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "media = (q_seguranca*s_seguranca + q_docente*s_docente + q_diretoria*s_diretoria) / (total_empregados)\n",
        "media"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "poo3h9Cx5Tex",
        "outputId": "a507c210-0137-49ec-e284-54920532a6bb"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "-7.967741935483871"
            ]
          },
          "metadata": {},
          "execution_count": 30
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "s1 = 'Alura '\n",
        "s2 = \"Alura\"\n",
        "print(type(s1),type(s2))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Sdo-qCMG7WJU",
        "outputId": "fc9c8289-3c40-405f-d227-52eb0e2fe04d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'str'> <class 'str'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "texto = 'Geovana Alessandra dias Sanyos '"
      ],
      "metadata": {
        "id": "XlkWuzMw9H3H"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "texto.upper()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "r5bl7m-_-qo3",
        "outputId": "1aadf47c-692b-4e62-b0ed-284ed4282b2f"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'GEOVANA ALESSANDRA DIAS SANYOS '"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 37
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "texto.lower()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "C_E5fQz_-6-8",
        "outputId": "b8a95890-ac85-40f0-d1b7-9895c73a36e3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'geovana alessandra dias sanyos '"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 38
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "texto.replace('y','t')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "41C_lIz9_BtL",
        "outputId": "bc4259d9-66d8-47f9-dd13-3212c88a3446"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Geovana Alessandra dias Santos '"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 41
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "texto = texto.strip().replace('y','t').upper()\n",
        "texto"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "d7pDgOsu_r5g",
        "outputId": "8db78bef-5ce2-4905-b72d-17c3add92eb2"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'GEOVANA ALESSANDRA DIAS SANTOS'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 42
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nome = input('Escreva seu nome: ')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "7HBSSjOHAnth",
        "outputId": "630ce839-25b2-4f2d-dd9f-842b56ed6333"
      },
      "execution_count": null,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Escreva seu nome: Paulo Henrique\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nome"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "2SEcPVC4BInw",
        "outputId": "623a80e5-73ff-421f-d68f-23b0bf68f250"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Paulo Henrique'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 44
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "ano_entrada = input('Escreva o ano de ingresso do(a) estudante:')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "7cYHSrEXBIlI",
        "outputId": "89500504-facf-4d26-e840-b307fc0f2664"
      },
      "execution_count": null,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Escreva o ano de ingresso do(a) estudante:2023\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "ano_entrada = int(input('Escreva o ano de ingresso do(a) estudante:'))\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Y9SWr8ZWB834",
        "outputId": "b1e46a76-50d2-44c3-9641-f8e5ebc49b88"
      },
      "execution_count": null,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Escreva o ano de ingresso do(a) estudante:2023\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "type(ano_entrada)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "BRYehEVCB81X",
        "outputId": "b3babae8-2f96-44c1-89a7-48a253de1c2d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "int"
            ]
          },
          "metadata": {},
          "execution_count": 48
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nota_entrada = float(input('Digite a nota do teste de ingresso: '))\n",
        "print(f'Ano de entrada {ano_entrada} - nota de teste de ingresso {nota_entrada}')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Pqm8JKcrC2Uu",
        "outputId": "6643e517-857b-4a3b-f3dc-a51c66241b64"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a nota do teste de ingresso: 9.0\n",
            "Ano de entrada 2023 - nota de teste de ingresso 9.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [],
      "metadata": {
        "id": "aUusRScwDJmV"
      }
    },
    {
      "cell_type": "markdown",
      "source": [],
      "metadata": {
        "id": "0L9UhCHgDJi5"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "if 2 >7:\n",
        "  print('condição verdadeira')\n",
        "  print()\n",
        "print('fora do bloco')"
      ],
      "metadata": {
        "id": "l4CU7ExUC2R7",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "a1259f77-8a22-47cc-b9ad-2943214d3f47"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "fora do bloco\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "media = float(input('Digite a media: '))\n",
        "if media >=6.0:\n",
        "  print('Aprovado')\n",
        "else:\n",
        "  print('Reprovado')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "DagcwSMrni6q",
        "outputId": "64364b15-abdf-418b-ee77-7aca170b1422"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a media: 6.0\n",
            "Aprovado\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "media = float(input('Digite a media: '))\n",
        "if media >= 6.0:\n",
        "   print('Aprovado')\n",
        "if 6.0 > media >= 4.0:\n",
        "    print('Recuperação')\n",
        "if media < 4.0:\n",
        "    print('Reprovado')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "6RKu5qSKpjCK",
        "outputId": "91eea12d-81c1-46b8-eaa3-2ce7782eac4b"
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a media: 6.0\n",
            "Aprovado\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "media = float(input('Digite a media: '))\n",
        "\n",
        "if media >= 6.0:\n",
        "   print('Aprovado')\n",
        "if 6.0 > media >= 4.0:\n",
        "    print('Recuperação')\n",
        "else:\n",
        "    print('Reprovado')"
      ],
      "metadata": {
        "id": "sCNVxEzBq_D4"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "media = float(input('Digite a media: '))\n",
        "if media >= 6.0:\n",
        "   print('Aprovado')\n",
        "elif 6.0 > media >= 4.0:\n",
        "    print('Recuperação')\n",
        "else:\n",
        "    print('Reprovado')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "w34YjxxEsC5q",
        "outputId": "f0483620-7dc1-4b10-dad0-f32a0541a51b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a media: 9\n",
            "Aprovado\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "t1 = t2 = True\n",
        "f1 =f2 = False\n"
      ],
      "metadata": {
        "id": "O4tWCB54ulVd"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "if t1 and f2:\n",
        "  print('expressâo verdadeira')\n",
        "else:\n",
        "  print('expressão falsa')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "HgRWiO08vKG2",
        "outputId": "24f343ae-1c01-4bc3-d302-6d522a9a96f3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "expressão falsa\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "if  t1 or f2:\n",
        "  print('expressâo verdadeira')\n",
        "else:\n",
        "  print('expressão falsa')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "eB5API4Fv8TV",
        "outputId": "37b5a29b-ba08-4b92-f87e-136661ec2a3c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "expressâo verdadeira\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "if not False:\n",
        "  print('expressâo verdadeira')\n",
        "else:\n",
        "  print('expressão falsa')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8CooQ3ULv9Ut",
        "outputId": "81c67519-c5c1-400b-8097-6c6376183e4e"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "expressâo verdadeira\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista = 'José da Silva, Maria Oliveira, Pedro Martins, Ana Souza, Carlos Rodrigues, Juliana Santos, Bruno Gomes, Beatriz Costa, Felipe Almeida, Mariana Fernandes, João Pinto, Luísa Nascimento, Gabriel Souza, Manuela Santos, Thiago Oliveira, Sofia Ferreira, Rafael Albuquerque, Isabella Gomes, Bruno Costa, Maria Martins, Rafaela Souza, Matheus Fernandes, Luísa Almeida, Beatriz Pinto, Mariana Rodrigues, Gabriel Nascimento, João Ferreira, Maria Albuquerque, Felipe Oliveira'\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 105
        },
        "id": "S97ota-kxUUI",
        "outputId": "a93fa73f-ed26-4109-a1c1-af8c52645c82"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'José da Silva, Maria Oliveira, Pedro Martins, Ana Souza, Carlos Rodrigues, Juliana Santos, Bruno Gomes, Beatriz Costa, Felipe Almeida, Mariana Fernandes, João Pinto, Luísa Nascimento, Gabriel Souza, Manuela Santos, Thiago Oliveira, Sofia Ferreira, Rafael Albuquerque, Isabella Gomes, Bruno Costa, Maria Martins, Rafaela Souza, Matheus Fernandes, Luísa Almeida, Beatriz Pinto, Mariana Rodrigues, Gabriel Nascimento, João Ferreira, Maria Albuquerque, Felipe Oliveira'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 36
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nome_1 = 'Mariana Rodrigues'\n",
        "nome_2 = 'Marcelo Nogueira'"
      ],
      "metadata": {
        "id": "826kjKWvxuD5"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "if nome_1 in lista:\n",
        "  print(f'{nome_1} esta na lista')\n",
        "else:\n",
        "  print(f'{nome_1} nao está na lista')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "TFXjbvvcyaQG",
        "outputId": "c48ab953-f707-4a02-e5f5-2d26f8ddfa59"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Marcelo Nogueira esta na lista\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "if nome_2 in lista:\n",
        "  print(f'{nome_2} esta na lista')\n",
        "else:\n",
        "  print(f'{nome_2} nao está na lista')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Pcwzh7ogzTDN",
        "outputId": "4cb70cbf-8ef5-494b-b738-101942908822"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Marcelo Nogueira nao está na lista\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "nota_1 =float(input('Digite a  1° nota: '))\n",
        "nota_2 =float(input('Digite a 2° nota: '))\n",
        "print(f'Media: {(nota_1+nota_2)/2}')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "x4DuIkYM1-g0",
        "outputId": "4462343e-264c-42da-d389-379a4702250f"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a  1° nota: 5\n",
            "Digite a 2° nota: 6\n",
            "Media: 5.5\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "contador = 1\n",
        "while contador <= 10:\n",
        "  print(contador)\n",
        "  contador += 1"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "LZiZLvTi4Dg9",
        "outputId": "22a7bb5e-b405-4751-b4d4-950fe9ffcbea"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "contador = 1\n",
        "while contador <=3:\n",
        " nota_1 =float(input('Digite a  1° nota: '))\n",
        " nota_2 =float(input('Digite a 2° nota: '))\n",
        " print(f'Media: {(nota_1+nota_2)/2}')\n",
        " contador+=1"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "g8KRxVl85pTE",
        "outputId": "ef087836-7a5f-43c4-b155-59d051f81902"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a  1° nota: 5\n",
            "Digite a 2° nota: 6\n",
            "Media: 5.5\n",
            "Digite a  1° nota: 7\n",
            "Digite a 2° nota: 9\n",
            "Media: 8.0\n",
            "Digite a  1° nota: 4\n",
            "Digite a 2° nota: 4\n",
            "Media: 4.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for contador in range(1,11):\n",
        "  print(contador)"
      ],
      "metadata": {
        "id": "ZSTlH-nk6qWx"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "for contador in range(1,4):\n",
        "  nota_1 =float(input('Digite a  1° nota: '))\n",
        "  nota_2 =float(input('Digite a 2° nota: '))\n",
        "print(f'Media: {(nota_1+nota_2)/2}')"
      ],
      "metadata": {
        "id": "UepcBlcF9AwE"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "lista = ['Fabricio Daniel', 9.5,9.0,8.0,True]\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "58evNCkp_Fi7",
        "outputId": "3fff6c14-9708-4356-e40a-94d148190995"
      },
      "execution_count": 3,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0, 8.0, True]"
            ]
          },
          "metadata": {},
          "execution_count": 3
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[0]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "Dfvl30YVAtBL",
        "outputId": "b6212f95-c1eb-4813-da31-57738cc6c2f3"
      },
      "execution_count": 4,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Fabricio Daniel'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 4
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[1]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "F_JWXjI8A1x8",
        "outputId": "6585e8fa-cdca-47bc-dc47-fbb9c0412418"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "9.5"
            ]
          },
          "metadata": {},
          "execution_count": 5
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[-1]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "s4gjPm-JA5M6",
        "outputId": "25cee49a-01c4-42fb-bebd-91fc50e0af9d"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "True"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for elemento in lista:\n",
        "  print(elemento)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wdD0GtDyBIAT",
        "outputId": "b0f72841-e34e-4266-b060-09de6487a391"
      },
      "execution_count": 8,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Fabricio Daniel\n",
            "9.5\n",
            "9.0\n",
            "8.0\n",
            "True\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[3] =10.0\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "tqagI0BUBbrw",
        "outputId": "39864e5a-2262-48b0-d128-dbc6ab629cc1"
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0, 10.0, True]"
            ]
          },
          "metadata": {},
          "execution_count": 10
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "media =(lista[1] +lista[2] +lista[3])/3\n",
        "media"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "MRYBFoLnBl4I",
        "outputId": "cdd916a7-0a36-424f-ff4e-7cebe8dba433"
      },
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "9.5"
            ]
          },
          "metadata": {},
          "execution_count": 12
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "len( lista)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "lXop19W2ENfZ",
        "outputId": "98a0f8b6-770a-4ec4-b74c-dec51f7f4023"
      },
      "execution_count": 13,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "5"
            ]
          },
          "metadata": {},
          "execution_count": 13
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[1:4]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "i8U7Y2FrE_H2",
        "outputId": "b1121cb7-917b-490b-9b1e-beda2be81924"
      },
      "execution_count": 14,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "[9.5, 9.0, 10.0]"
            ]
          },
          "metadata": {},
          "execution_count": 14
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[1:3]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_NjGaYx-Fq79",
        "outputId": "c3b68e76-6923-4071-98c4-ae2647f40bad"
      },
      "execution_count": 16,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "[9.5, 9.0]"
            ]
          },
          "metadata": {},
          "execution_count": 16
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[:3]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "6hLeJMDUF5OU",
        "outputId": "fcd86b73-10ee-421a-f232-1683f088bbb6"
      },
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0]"
            ]
          },
          "metadata": {},
          "execution_count": 17
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[3:]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "xpTv2mpPF_QZ",
        "outputId": "98ca4579-40e0-40ef-cb85-fca0bf93be98"
      },
      "execution_count": 18,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "[10.0, True]"
            ]
          },
          "metadata": {},
          "execution_count": 18
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista[:]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zJSgN7i6GFJI",
        "outputId": "a2d4cc3c-40cb-4f91-aa61-6ea4bc340ed4"
      },
      "execution_count": 19,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0, 10.0, True]"
            ]
          },
          "metadata": {},
          "execution_count": 19
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista.append(media)\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "QPG4LkA1IVk-",
        "outputId": "39d4998c-5b96-481f-9549-2c2777bb9e3a"
      },
      "execution_count": 21,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0, 10.0, True, 9.5, 9.5]"
            ]
          },
          "metadata": {},
          "execution_count": 21
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista.extend([10.0,8.0,9.0])\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "6pt18IreIq_T",
        "outputId": "b66b7440-a4fa-403e-862b-da9c595bc1b5"
      },
      "execution_count": 22,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel', 9.5, 9.0, 10.0, True, 9.5, 9.5, 10.0, 8.0, 9.0]"
            ]
          },
          "metadata": {},
          "execution_count": 22
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista.append([10.0,9.5,9.0,8.0])\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "jzIKk1E0Ja-A",
        "outputId": "3f056ee8-0bce-443d-affc-05ebca2cbe26"
      },
      "execution_count": 24,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel',\n",
              " 9.5,\n",
              " 9.0,\n",
              " 10.0,\n",
              " True,\n",
              " 9.5,\n",
              " 9.5,\n",
              " 10.0,\n",
              " 8.0,\n",
              " 9.0,\n",
              " [9.5, 9.0, 8.0],\n",
              " [10.0, 9.5, 9.0, 8.0]]"
            ]
          },
          "metadata": {},
          "execution_count": 24
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "lista.remove([10.0, 9.5, 9.0, 8.0])\n",
        "lista"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Cqabr4MFJp9W",
        "outputId": "6fdc3ac6-39e7-4fc0-ccb4-3de86c866bdb"
      },
      "execution_count": 27,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['Fabricio Daniel',\n",
              " 9.5,\n",
              " 9.0,\n",
              " 10.0,\n",
              " True,\n",
              " 9.5,\n",
              " 9.5,\n",
              " 10.0,\n",
              " 8.0,\n",
              " 9.0,\n",
              " [9.5, 9.0, 8.0]]"
            ]
          },
          "metadata": {},
          "execution_count": 27
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "dicionario = {'chave_1' :1, 'chave_2' :2}\n",
        "dicionario"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "LOXgTHoYKWhg",
        "outputId": "9fa7ced9-fba9-4039-9d77-fdcf3eddf89b"
      },
      "execution_count": 34,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'chave_1': 1, 'chave_2': 2}"
            ]
          },
          "metadata": {},
          "execution_count": 34
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro = {'matricula': 2000168933,\n",
        "              'dia_cadastro':25,\n",
        "              'mes_cadastro':10,\n",
        "              'turma':'2E'}\n",
        "cadastro"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Ozls6g8eLiej",
        "outputId": "e1b53d67-4b08-454e-f668-1a3e1ee61eef"
      },
      "execution_count": 39,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'matricula': 2000168933,\n",
              " 'dia_cadastro': 25,\n",
              " 'mes_cadastro': 10,\n",
              " 'turma': '2E'}"
            ]
          },
          "metadata": {},
          "execution_count": 39
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro['matricula']"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9VNkrtsZNGFH",
        "outputId": "5dc9d26b-75de-42f8-f828-33676b9acaf9"
      },
      "execution_count": 40,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "2000168933"
            ]
          },
          "metadata": {},
          "execution_count": 40
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro['turma']"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "OeL8weRiOFPc",
        "outputId": "0da749cd-a406-481b-a0e6-321aa6eb0d24"
      },
      "execution_count": 41,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'2E'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 41
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro['turma'] ='2G'\n",
        "cadastro"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "k1_FjOPGOI8z",
        "outputId": "a9da92e8-a05f-4a63-ea29-c73614ebbc91"
      },
      "execution_count": 42,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'matricula': 2000168933,\n",
              " 'dia_cadastro': 25,\n",
              " 'mes_cadastro': 10,\n",
              " 'turma': '2G'}"
            ]
          },
          "metadata": {},
          "execution_count": 42
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro['modalidade'] ='EAD'\n",
        "cadastro"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "1zVSOhU0OeS4",
        "outputId": "7b6c1c26-c3a4-4efa-ba3a-4614f93daee1"
      },
      "execution_count": 43,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'matricula': 2000168933,\n",
              " 'dia_cadastro': 25,\n",
              " 'mes_cadastro': 10,\n",
              " 'turma': '2G',\n",
              " 'modalidade': 'EAD'}"
            ]
          },
          "metadata": {},
          "execution_count": 43
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro.pop( 'turma')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 35
        },
        "id": "lxLHkHXcOvzh",
        "outputId": "a635e51f-e6d1-442a-b6e9-c60609ca4774"
      },
      "execution_count": 44,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'2G'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 44
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wV5Km71OPruO",
        "outputId": "4ef147cc-f129-419d-8c10-f2487ed1da79"
      },
      "execution_count": 45,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'matricula': 2000168933,\n",
              " 'dia_cadastro': 25,\n",
              " 'mes_cadastro': 10,\n",
              " 'modalidade': 'EAD'}"
            ]
          },
          "metadata": {},
          "execution_count": 45
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro.items()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "otIH8tlIPumk",
        "outputId": "5e5ff960-546a-40eb-bb56-8d08eb4b9e55"
      },
      "execution_count": 47,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "dict_items([('matricula', 2000168933), ('dia_cadastro', 25), ('mes_cadastro', 10), ('modalidade', 'EAD')])"
            ]
          },
          "metadata": {},
          "execution_count": 47
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro.keys()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kuGfIWomQhwY",
        "outputId": "abdf8a52-6ede-434d-8e27-5e79b20d5773"
      },
      "execution_count": 48,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "dict_keys(['matricula', 'dia_cadastro', 'mes_cadastro', 'modalidade'])"
            ]
          },
          "metadata": {},
          "execution_count": 48
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "cadastro.values()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "nlvsGjUVQsza",
        "outputId": "1a7fb8cb-fe74-4cdc-97e1-77ce0f34f040"
      },
      "execution_count": 49,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "dict_values([2000168933, 25, 10, 'EAD'])"
            ]
          },
          "metadata": {},
          "execution_count": 49
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for chaves in cadastro.keys():\n",
        "  print(cadastro[chaves])"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "S9O01N9sQxhj",
        "outputId": "b22341b9-7d22-40df-d9a3-e351e7f4d5b0"
      },
      "execution_count": 50,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2000168933\n",
            "25\n",
            "10\n",
            "EAD\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for valores in cadastro.values():\n",
        " print(valores)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Ab8RHdVERnkJ",
        "outputId": "ddbf9738-5c20-4ce8-dc10-bfd4ca38f964"
      },
      "execution_count": 53,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2000168933\n",
            "25\n",
            "10\n",
            "EAD\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for chaves, valores in cadastro.items():\n",
        "  print(chaves, valores)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "NQohYTHZSRHj",
        "outputId": "21cf058c-ca0f-4037-c4cb-8b2ba262c494"
      },
      "execution_count": 54,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "matricula 2000168933\n",
            "dia_cadastro 25\n",
            "mes_cadastro 10\n",
            "modalidade EAD\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "ZBiL_WPATIwj"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}# Python-para-Data-Science-primeiros-passos

