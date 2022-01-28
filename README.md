# Data-Analysis-with-Python

{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "7c68bbfd",
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "bffc41d0",
   "metadata": {},
   "outputs": [],
   "source": [
    "import pandas as pd"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "25a8138f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "LS\n"
     ]
    }
   ],
   "source": [
    "print(\"LS\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "aa4a67e4",
   "metadata": {},
   "outputs": [],
   "source": [
    "ar=np.array([1,2,3])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "888d78d9",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([1, 2, 3])"
      ]
     },
     "execution_count": 5,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "ar"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "76b46b1e",
   "metadata": {},
   "outputs": [],
   "source": [
    "a = np.arange(20)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "id": "9d6d35ea",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([ 0,  1,  2,  3,  4,  5,  6,  7,  8,  9, 10, 11, 12, 13, 14, 15, 16,\n",
       "       17, 18, 19])"
      ]
     },
     "execution_count": 17,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "id": "9b57280d",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "numpy.ndarray"
      ]
     },
     "execution_count": 18,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "type(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "id": "d288aff4",
   "metadata": {},
   "outputs": [],
   "source": [
    "df = pd.DataFrame(np.random.randn(6, 4))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "id": "4f673d6c",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "      <th>3</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>0.055466</td>\n",
       "      <td>-0.222731</td>\n",
       "      <td>1.622826</td>\n",
       "      <td>-1.691045</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.847786</td>\n",
       "      <td>-0.286525</td>\n",
       "      <td>0.791751</td>\n",
       "      <td>-0.139972</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.473503</td>\n",
       "      <td>0.403243</td>\n",
       "      <td>2.665888</td>\n",
       "      <td>0.199606</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>1.337790</td>\n",
       "      <td>0.392878</td>\n",
       "      <td>-0.461451</td>\n",
       "      <td>-0.254678</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>0.164323</td>\n",
       "      <td>-0.719443</td>\n",
       "      <td>-2.143228</td>\n",
       "      <td>-0.355823</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>1.251113</td>\n",
       "      <td>0.561528</td>\n",
       "      <td>-1.317885</td>\n",
       "      <td>-1.046423</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "          0         1         2         3\n",
       "0  0.055466 -0.222731  1.622826 -1.691045\n",
       "1  0.847786 -0.286525  0.791751 -0.139972\n",
       "2  0.473503  0.403243  2.665888  0.199606\n",
       "3  1.337790  0.392878 -0.461451 -0.254678\n",
       "4  0.164323 -0.719443 -2.143228 -0.355823\n",
       "5  1.251113  0.561528 -1.317885 -1.046423"
      ]
     },
     "execution_count": 20,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "e13b6cef",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "      <th>3</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>0.055466</td>\n",
       "      <td>-0.222731</td>\n",
       "      <td>1.622826</td>\n",
       "      <td>-1.691045</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.847786</td>\n",
       "      <td>-0.286525</td>\n",
       "      <td>0.791751</td>\n",
       "      <td>-0.139972</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.473503</td>\n",
       "      <td>0.403243</td>\n",
       "      <td>2.665888</td>\n",
       "      <td>0.199606</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>1.337790</td>\n",
       "      <td>0.392878</td>\n",
       "      <td>-0.461451</td>\n",
       "      <td>-0.254678</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>0.164323</td>\n",
       "      <td>-0.719443</td>\n",
       "      <td>-2.143228</td>\n",
       "      <td>-0.355823</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>1.251113</td>\n",
       "      <td>0.561528</td>\n",
       "      <td>-1.317885</td>\n",
       "      <td>-1.046423</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "          0         1         2         3\n",
       "0  0.055466 -0.222731  1.622826 -1.691045\n",
       "1  0.847786 -0.286525  0.791751 -0.139972\n",
       "2  0.473503  0.403243  2.665888  0.199606\n",
       "3  1.337790  0.392878 -0.461451 -0.254678\n",
       "4  0.164323 -0.719443 -2.143228 -0.355823\n",
       "5  1.251113  0.561528 -1.317885 -1.046423"
      ]
     },
     "execution_count": 21,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "id": "6687b973",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "      <th>3</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>0.055466</td>\n",
       "      <td>-0.222731</td>\n",
       "      <td>1.622826</td>\n",
       "      <td>-1.691045</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.847786</td>\n",
       "      <td>-0.286525</td>\n",
       "      <td>0.791751</td>\n",
       "      <td>-0.139972</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.473503</td>\n",
       "      <td>0.403243</td>\n",
       "      <td>2.665888</td>\n",
       "      <td>0.199606</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>1.337790</td>\n",
       "      <td>0.392878</td>\n",
       "      <td>-0.461451</td>\n",
       "      <td>-0.254678</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>0.164323</td>\n",
       "      <td>-0.719443</td>\n",
       "      <td>-2.143228</td>\n",
       "      <td>-0.355823</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>1.251113</td>\n",
       "      <td>0.561528</td>\n",
       "      <td>-1.317885</td>\n",
       "      <td>-1.046423</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "          0         1         2         3\n",
       "0  0.055466 -0.222731  1.622826 -1.691045\n",
       "1  0.847786 -0.286525  0.791751 -0.139972\n",
       "2  0.473503  0.403243  2.665888  0.199606\n",
       "3  1.337790  0.392878 -0.461451 -0.254678\n",
       "4  0.164323 -0.719443 -2.143228 -0.355823\n",
       "5  1.251113  0.561528 -1.317885 -1.046423"
      ]
     },
     "execution_count": 22,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "id": "6f2a6c94",
   "metadata": {},
   "outputs": [],
   "source": [
    "df = pd.read_csv('P1-OfficeSupplies.csv')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "id": "de0471d7",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>Unit Price</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>4-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>62</td>\n",
       "      <td>4.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>12-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Nick</td>\n",
       "      <td>Binder</td>\n",
       "      <td>29</td>\n",
       "      <td>1.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>21-Jul-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>55</td>\n",
       "      <td>12.49</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>29-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>81</td>\n",
       "      <td>19.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>7-Aug-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>42</td>\n",
       "      <td>23.95</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "     OrderDate   Region      Rep     Item  Units  Unit Price\n",
       "0   4-Jul-2014     East  Richard  Pen Set     62        4.99\n",
       "1  12-Jul-2014     East     Nick   Binder     29        1.99\n",
       "2  21-Jul-2014  Central   Morgan  Pen Set     55       12.49\n",
       "3  29-Jul-2014     East    Susan   Binder     81       19.99\n",
       "4   7-Aug-2014  Central  Matthew  Pen Set     42       23.95"
      ]
     },
     "execution_count": 24,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.head(5)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "d234913e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>Unit Price</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>38</th>\n",
       "      <td>22-May-2015</td>\n",
       "      <td>West</td>\n",
       "      <td>Thomas</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>32</td>\n",
       "      <td>1.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>39</th>\n",
       "      <td>31-May-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Binder</td>\n",
       "      <td>80</td>\n",
       "      <td>8.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>40</th>\n",
       "      <td>8-Jun-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Binder</td>\n",
       "      <td>60</td>\n",
       "      <td>8.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>41</th>\n",
       "      <td>17-Jun-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Desk</td>\n",
       "      <td>5</td>\n",
       "      <td>125.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>42</th>\n",
       "      <td>25-Jun-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>90</td>\n",
       "      <td>4.99</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      OrderDate   Region      Rep    Item  Units  Unit Price\n",
       "38  22-May-2015     West   Thomas  Pencil     32        1.99\n",
       "39  31-May-2015  Central     Bill  Binder     80        8.99\n",
       "40   8-Jun-2015     East  Richard  Binder     60        8.99\n",
       "41  17-Jun-2015  Central  Matthew    Desk      5      125.00\n",
       "42  25-Jun-2015  Central   Morgan  Pencil     90        4.99"
      ]
     },
     "execution_count": 25,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.tail(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "fc19daab",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "id": "b0496713",
   "metadata": {},
   "outputs": [
    {
     "ename": "NameError",
     "evalue": "name 'df2' is not defined",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mNameError\u001b[0m                                 Traceback (most recent call last)",
      "Input \u001b[1;32mIn [26]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m \u001b[43mdf2\u001b[49m\n",
      "\u001b[1;31mNameError\u001b[0m: name 'df2' is not defined"
     ]
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "id": "d2831e57",
   "metadata": {},
   "outputs": [
    {
     "ename": "NameError",
     "evalue": "name 'df2' is not defined",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mNameError\u001b[0m                                 Traceback (most recent call last)",
      "Input \u001b[1;32mIn [27]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m \u001b[43mdf2\u001b[49m\u001b[38;5;241m.\u001b[39mtail(\u001b[38;5;241m2\u001b[39m)\n",
      "\u001b[1;31mNameError\u001b[0m: name 'df2' is not defined"
     ]
    }
   ],
   "source": [
    "df2.tail(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "9880808c",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.head(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "3d369781",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.columns"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f27c1d36",
   "metadata": {},
   "outputs": [],
   "source": [
    "print(df.columns)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "98e87b14",
   "metadata": {},
   "outputs": [],
   "source": [
    "\n",
    "df.columns[0,4]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4b789077",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.columns"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4a2ce462",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2['Rep'].tail(5).head(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "40b244a9",
   "metadata": {},
   "outputs": [],
   "source": [
    "df[\"Rep\"][0:15]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "97593890",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.size"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "abad26b1",
   "metadata": {},
   "outputs": [],
   "source": [
    "df"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c5756246",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2[['Rep', 'Item', 'Units']].head(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "70e5d330",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.iloc[1,2]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c3a77833",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.head(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "47852fa1",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.describe()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "17c26983",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "37af357a",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.sort_values('Rep').head(15)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "20855d3c",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.sort_values(['Rep', 'Item'], ascending=True).head(10\n",
    "                                                     )"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "56854f81",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.sort_values('Rep', ascending=False).head(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "e22625b5",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f184f6ee",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "2904a8fb",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.describe()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "id": "799741f8",
   "metadata": {},
   "outputs": [],
   "source": [
    "data = {\n",
    "  \"ID\": [\"100\",\"101\",\"102\",\"103\",\"104\",\"105\"],\n",
    "  \"NAME\": [\"RAM\",\"SHYAM\",\"SHIV\",\"KRISHNA\",\"RADHA\",\"KANHA\"],\n",
    "  \"SKILL\": [\"WEB\",\"HTML\",\"CSS\",\"JS\",\"PY\",\"JAVA\"]\n",
    "}"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "id": "cfe1d56b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'ID': ['100', '101', '102', '103', '104', '105'],\n",
       " 'NAME': ['RAM', 'SHYAM', 'SHIV', 'KRISHNA', 'RADHA', 'KANHA'],\n",
       " 'SKILL': ['WEB', 'HTML', 'CSS', 'JS', 'PY', 'JAVA']}"
      ]
     },
     "execution_count": 29,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "data"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "id": "531bb214",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2 = pd.DataFrame(data)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "id": "4d76d0f2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100      RAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 31,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 32,
   "id": "aaca0c62",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2[\"NAME\"][0] = \"Raghav\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "id": "68bdffd4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>Raghav</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100   Raghav   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 33,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "id": "48120254",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>Raghav</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID    NAME SKILL\n",
       "0  100  Raghav   WEB\n",
       "1  101   SHYAM  HTML"
      ]
     },
     "execution_count": 34,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.head(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "id": "b3af05f7",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID   NAME SKILL\n",
       "4  104  RADHA    PY\n",
       "5  105  KANHA  JAVA"
      ]
     },
     "execution_count": 35,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.tail(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "id": "73cd3e95",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>count</th>\n",
       "      <td>6</td>\n",
       "      <td>6</td>\n",
       "      <td>6</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>unique</th>\n",
       "      <td>6</td>\n",
       "      <td>6</td>\n",
       "      <td>6</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>top</th>\n",
       "      <td>100</td>\n",
       "      <td>Raghav</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>freq</th>\n",
       "      <td>1</td>\n",
       "      <td>1</td>\n",
       "      <td>1</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "         ID    NAME SKILL\n",
       "count     6       6     6\n",
       "unique    6       6     6\n",
       "top     100  Raghav   WEB\n",
       "freq      1       1     1"
      ]
     },
     "execution_count": 36,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.describe()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 37,
   "id": "0868fce1",
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100      RAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 37,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2[\"NAME\"][0] = \"RAM\"\n",
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "id": "f90685da",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.to_csv(\"df2.csv\", index=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "id": "39d6fdb8",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2[\"NAME\"][0] = \"RAGHAV\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "id": "59af861e",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.to_csv(\"df2.csv\", index=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "id": "169c2e49",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAGHAV</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100   RAGHAV   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 41,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "pd.read_csv(\"df2.csv\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "id": "33941703",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2[\"NAME\"][0]=\"RAAM\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "id": "35c22c25",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.to_csv(\"df2.csv\", index=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "id": "b3802ed4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 44,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "id": "ff0b936d",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.index = [\"1st\",\"2nd\",\"3rd\",\"4th\",\"5th\",\"6th\"]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 46,
   "id": "3617416c",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "1st  100     RAAM   WEB\n",
       "2nd  101    SHYAM  HTML\n",
       "3rd  102     SHIV   CSS\n",
       "4th  103  KRISHNA    JS\n",
       "5th  104    RADHA    PY\n",
       "6th  105    KANHA  JAVA"
      ]
     },
     "execution_count": 46,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    " df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "id": "28eabfe1",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.to_csv(\"df2.csv\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "id": "ccaeea52",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Index(['1st', '2nd', '3rd', '4th', '5th', '6th'], dtype='object')"
      ]
     },
     "execution_count": 48,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.index"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "id": "88a71f30",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'RAAM'"
      ]
     },
     "execution_count": 49,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2[\"NAME\"][\"1st\"]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 50,
   "id": "c32415af",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "1st  100     RAAM   WEB\n",
       "2nd  101    SHYAM  HTML\n",
       "3rd  102     SHIV   CSS\n",
       "4th  103  KRISHNA    JS\n",
       "5th  104    RADHA    PY\n",
       "6th  105    KANHA  JAVA"
      ]
     },
     "execution_count": 50,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 51,
   "id": "2d174bb4",
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 52,
   "id": "590cb03c",
   "metadata": {},
   "outputs": [],
   "source": [
    "r = np.random.rand(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 53,
   "id": "bbe3f10b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([0.45623476, 0.75218627])"
      ]
     },
     "execution_count": 53,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 54,
   "id": "79f5308d",
   "metadata": {},
   "outputs": [],
   "source": [
    "r = np.random.randn(2,2) * 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 55,
   "id": "db6c5606",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([[0.06667249, 0.0379546 ],\n",
       "       [0.40194896, 0.44165844]])"
      ]
     },
     "execution_count": 55,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r*r"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "id": "c789b722",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([[ 0.25821016,  0.19481941],\n",
       "       [-0.63399445, -0.66457388]])"
      ]
     },
     "execution_count": 56,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 57,
   "id": "30efe796",
   "metadata": {},
   "outputs": [],
   "source": [
    "r = np.random.randint(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 58,
   "id": "5b121343",
   "metadata": {},
   "outputs": [],
   "source": [
    "r = pd.Series(np.random.rand(5))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 59,
   "id": "f3e4f007",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0    0.662096\n",
       "1    0.998455\n",
       "2    0.373190\n",
       "3    0.593248\n",
       "4    0.713344\n",
       "dtype: float64"
      ]
     },
     "execution_count": 59,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "id": "65831cf7",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "pandas.core.series.Series"
      ]
     },
     "execution_count": 60,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "type(r)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 61,
   "id": "762cf878",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "pandas.core.frame.DataFrame"
      ]
     },
     "execution_count": 61,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "type(df2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 62,
   "id": "2cc47086",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "RangeIndex(start=0, stop=5, step=1)"
      ]
     },
     "execution_count": 62,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    " r.index"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 63,
   "id": "1d097ec7",
   "metadata": {},
   "outputs": [
    {
     "ename": "ValueError",
     "evalue": "DataFrame constructor not properly called!",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mValueError\u001b[0m                                Traceback (most recent call last)",
      "Input \u001b[1;32mIn [63]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m newdf \u001b[38;5;241m=\u001b[39m \u001b[43mpd\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mDataFrame\u001b[49m\u001b[43m(\u001b[49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[38;5;124;43m10,10\u001b[39;49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[43m)\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\frame.py:757\u001b[0m, in \u001b[0;36mDataFrame.__init__\u001b[1;34m(self, data, index, columns, dtype, copy)\u001b[0m\n\u001b[0;32m    754\u001b[0m \u001b[38;5;66;03m# For data is scalar\u001b[39;00m\n\u001b[0;32m    755\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n\u001b[0;32m    756\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m index \u001b[38;5;129;01mis\u001b[39;00m \u001b[38;5;28;01mNone\u001b[39;00m \u001b[38;5;129;01mor\u001b[39;00m columns \u001b[38;5;129;01mis\u001b[39;00m \u001b[38;5;28;01mNone\u001b[39;00m:\n\u001b[1;32m--> 757\u001b[0m         \u001b[38;5;28;01mraise\u001b[39;00m \u001b[38;5;167;01mValueError\u001b[39;00m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mDataFrame constructor not properly called!\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n\u001b[0;32m    759\u001b[0m     \u001b[38;5;66;03m# Argument 1 to \"ensure_index\" has incompatible type \"Collection[Any]\";\u001b[39;00m\n\u001b[0;32m    760\u001b[0m     \u001b[38;5;66;03m# expected \"Union[Union[Union[ExtensionArray, ndarray],\u001b[39;00m\n\u001b[0;32m    761\u001b[0m     \u001b[38;5;66;03m# Index, Series], Sequence[Any]]\"\u001b[39;00m\n\u001b[0;32m    762\u001b[0m     index \u001b[38;5;241m=\u001b[39m ensure_index(index)  \u001b[38;5;66;03m# type: ignore[arg-type]\u001b[39;00m\n",
      "\u001b[1;31mValueError\u001b[0m: DataFrame constructor not properly called!"
     ]
    }
   ],
   "source": [
    "newdf = pd.DataFrame(\"10,10\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 65,
   "id": "0a27ac72",
   "metadata": {},
   "outputs": [],
   "source": [
    "newdf = pd.DataFrame(np.random.rand(334,5), index=np.arange(334))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 66,
   "id": "5623c4bf",
   "metadata": {},
   "outputs": [],
   "source": [
    "newdf.to_csv(\"newdf.csv\", index=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "id": "832c0396",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "      <th>3</th>\n",
       "      <th>4</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>0.276973</td>\n",
       "      <td>0.635500</td>\n",
       "      <td>0.433397</td>\n",
       "      <td>0.786315</td>\n",
       "      <td>0.174373</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.784517</td>\n",
       "      <td>0.205708</td>\n",
       "      <td>0.480695</td>\n",
       "      <td>0.298703</td>\n",
       "      <td>0.946613</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.214027</td>\n",
       "      <td>0.491226</td>\n",
       "      <td>0.008148</td>\n",
       "      <td>0.576833</td>\n",
       "      <td>0.716628</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>0.461156</td>\n",
       "      <td>0.909184</td>\n",
       "      <td>0.385917</td>\n",
       "      <td>0.815771</td>\n",
       "      <td>0.219046</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>0.473573</td>\n",
       "      <td>0.979967</td>\n",
       "      <td>0.378670</td>\n",
       "      <td>0.947598</td>\n",
       "      <td>0.287301</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>...</th>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>329</th>\n",
       "      <td>0.284787</td>\n",
       "      <td>0.766265</td>\n",
       "      <td>0.718296</td>\n",
       "      <td>0.784324</td>\n",
       "      <td>0.558992</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>330</th>\n",
       "      <td>0.939890</td>\n",
       "      <td>0.736271</td>\n",
       "      <td>0.066299</td>\n",
       "      <td>0.218449</td>\n",
       "      <td>0.367921</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>331</th>\n",
       "      <td>0.513277</td>\n",
       "      <td>0.533884</td>\n",
       "      <td>0.336372</td>\n",
       "      <td>0.722513</td>\n",
       "      <td>0.302354</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>332</th>\n",
       "      <td>0.169494</td>\n",
       "      <td>0.039467</td>\n",
       "      <td>0.594737</td>\n",
       "      <td>0.389507</td>\n",
       "      <td>0.063771</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>333</th>\n",
       "      <td>0.846440</td>\n",
       "      <td>0.216845</td>\n",
       "      <td>0.718179</td>\n",
       "      <td>0.562055</td>\n",
       "      <td>0.326711</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "<p>334 rows × 5 columns</p>\n",
       "</div>"
      ],
      "text/plain": [
       "            0         1         2         3         4\n",
       "0    0.276973  0.635500  0.433397  0.786315  0.174373\n",
       "1    0.784517  0.205708  0.480695  0.298703  0.946613\n",
       "2    0.214027  0.491226  0.008148  0.576833  0.716628\n",
       "3    0.461156  0.909184  0.385917  0.815771  0.219046\n",
       "4    0.473573  0.979967  0.378670  0.947598  0.287301\n",
       "..        ...       ...       ...       ...       ...\n",
       "329  0.284787  0.766265  0.718296  0.784324  0.558992\n",
       "330  0.939890  0.736271  0.066299  0.218449  0.367921\n",
       "331  0.513277  0.533884  0.336372  0.722513  0.302354\n",
       "332  0.169494  0.039467  0.594737  0.389507  0.063771\n",
       "333  0.846440  0.216845  0.718179  0.562055  0.326711\n",
       "\n",
       "[334 rows x 5 columns]"
      ]
     },
     "execution_count": 67,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "pd.read_csv(\"newdf.csv\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 68,
   "id": "ddebdde7",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "      <th>3</th>\n",
       "      <th>4</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>count</th>\n",
       "      <td>334.000000</td>\n",
       "      <td>334.000000</td>\n",
       "      <td>334.000000</td>\n",
       "      <td>334.000000</td>\n",
       "      <td>334.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>mean</th>\n",
       "      <td>0.495851</td>\n",
       "      <td>0.498072</td>\n",
       "      <td>0.509767</td>\n",
       "      <td>0.513732</td>\n",
       "      <td>0.469544</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>std</th>\n",
       "      <td>0.286489</td>\n",
       "      <td>0.288853</td>\n",
       "      <td>0.287994</td>\n",
       "      <td>0.284892</td>\n",
       "      <td>0.292923</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>min</th>\n",
       "      <td>0.000258</td>\n",
       "      <td>0.007869</td>\n",
       "      <td>0.008148</td>\n",
       "      <td>0.001545</td>\n",
       "      <td>0.001957</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>25%</th>\n",
       "      <td>0.239628</td>\n",
       "      <td>0.242436</td>\n",
       "      <td>0.255542</td>\n",
       "      <td>0.281904</td>\n",
       "      <td>0.212852</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>50%</th>\n",
       "      <td>0.499031</td>\n",
       "      <td>0.517703</td>\n",
       "      <td>0.512649</td>\n",
       "      <td>0.520251</td>\n",
       "      <td>0.438966</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>75%</th>\n",
       "      <td>0.736453</td>\n",
       "      <td>0.735055</td>\n",
       "      <td>0.740685</td>\n",
       "      <td>0.758013</td>\n",
       "      <td>0.732933</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>max</th>\n",
       "      <td>0.999726</td>\n",
       "      <td>0.997733</td>\n",
       "      <td>0.997373</td>\n",
       "      <td>0.991244</td>\n",
       "      <td>0.996227</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "                0           1           2           3           4\n",
       "count  334.000000  334.000000  334.000000  334.000000  334.000000\n",
       "mean     0.495851    0.498072    0.509767    0.513732    0.469544\n",
       "std      0.286489    0.288853    0.287994    0.284892    0.292923\n",
       "min      0.000258    0.007869    0.008148    0.001545    0.001957\n",
       "25%      0.239628    0.242436    0.255542    0.281904    0.212852\n",
       "50%      0.499031    0.517703    0.512649    0.520251    0.438966\n",
       "75%      0.736453    0.735055    0.740685    0.758013    0.732933\n",
       "max      0.999726    0.997733    0.997373    0.991244    0.996227"
      ]
     },
     "execution_count": 68,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "newdf.describe()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 69,
   "id": "76cff042",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0    float64\n",
       "1    float64\n",
       "2    float64\n",
       "3    float64\n",
       "4    float64\n",
       "dtype: object"
      ]
     },
     "execution_count": 69,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "newdf.dtypes"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "id": "b0401fce",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Index(['1st', '2nd', '3rd', '4th', '5th', '6th'], dtype='object')"
      ]
     },
     "execution_count": 70,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.index"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 71,
   "id": "44fb99a9",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "RangeIndex(start=0, stop=43, step=1)"
      ]
     },
     "execution_count": 71,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.index"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 72,
   "id": "5e252cbb",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Int64Index([  0,   1,   2,   3,   4,   5,   6,   7,   8,   9,\n",
       "            ...\n",
       "            324, 325, 326, 327, 328, 329, 330, 331, 332, 333],\n",
       "           dtype='int64', length=334)"
      ]
     },
     "execution_count": 72,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "newdf.index"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 73,
   "id": "7b41c77c",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Index(['ID', 'NAME', 'SKILL'], dtype='object')"
      ]
     },
     "execution_count": 73,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.columns"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 74,
   "id": "947cadb2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "RangeIndex(start=0, stop=5, step=1)"
      ]
     },
     "execution_count": 74,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "newdf.columns"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 75,
   "id": "432db6ad",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "1st  100     RAAM   WEB\n",
       "2nd  101    SHYAM  HTML\n",
       "3rd  102     SHIV   CSS\n",
       "4th  103  KRISHNA    JS\n",
       "5th  104    RADHA    PY\n",
       "6th  105    KANHA  JAVA"
      ]
     },
     "execution_count": 75,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 76,
   "id": "8e5c31c4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>1st</th>\n",
       "      <th>2nd</th>\n",
       "      <th>3rd</th>\n",
       "      <th>4th</th>\n",
       "      <th>5th</th>\n",
       "      <th>6th</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>ID</th>\n",
       "      <td>100</td>\n",
       "      <td>101</td>\n",
       "      <td>102</td>\n",
       "      <td>103</td>\n",
       "      <td>104</td>\n",
       "      <td>105</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>NAME</th>\n",
       "      <td>RAAM</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>KANHA</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>SKILL</th>\n",
       "      <td>WEB</td>\n",
       "      <td>HTML</td>\n",
       "      <td>CSS</td>\n",
       "      <td>JS</td>\n",
       "      <td>PY</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "        1st    2nd   3rd      4th    5th    6th\n",
       "ID      100    101   102      103    104    105\n",
       "NAME   RAAM  SHYAM  SHIV  KRISHNA  RADHA  KANHA\n",
       "SKILL   WEB   HTML   CSS       JS     PY   JAVA"
      ]
     },
     "execution_count": 76,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.T"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 77,
   "id": "abd1b4b1",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1st    100\n",
       "2nd    101\n",
       "3rd    102\n",
       "4th    103\n",
       "5th    104\n",
       "6th    105\n",
       "Name: ID, dtype: object"
      ]
     },
     "execution_count": 77,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2[\"ID\"]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 78,
   "id": "8ff866c9",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "1st  100     RAAM   WEB\n",
       "2nd  101    SHYAM  HTML\n",
       "3rd  102     SHIV   CSS\n",
       "4th  103  KRISHNA    JS\n",
       "5th  104    RADHA    PY\n",
       "6th  105    KANHA  JAVA"
      ]
     },
     "execution_count": 78,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 79,
   "id": "bce181a2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "6th  105    KANHA  JAVA\n",
       "5th  104    RADHA    PY\n",
       "4th  103  KRISHNA    JS\n",
       "3rd  102     SHIV   CSS\n",
       "2nd  101    SHYAM  HTML\n",
       "1st  100     RAAM   WEB"
      ]
     },
     "execution_count": 79,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.sort_index(axis=0, ascending=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 80,
   "id": "a5069a9a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "6th  105    KANHA  JAVA\n",
       "5th  104    RADHA    PY\n",
       "4th  103  KRISHNA    JS\n",
       "3rd  102     SHIV   CSS\n",
       "2nd  101    SHYAM  HTML\n",
       "1st  100     RAAM   WEB"
      ]
     },
     "execution_count": 80,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.sort_index(axis=0, ascending=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "db2efd04",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 81,
   "id": "60386607",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.index = list('012345')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 82,
   "id": "ad975f8b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 82,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 83,
   "id": "3a13a1cb",
   "metadata": {},
   "outputs": [
    {
     "ename": "KeyError",
     "evalue": "\"None of [Int64Index([1], dtype='int64')] are in the [index]\"",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mKeyError\u001b[0m                                  Traceback (most recent call last)",
      "Input \u001b[1;32mIn [83]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m \u001b[43mdf2\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mloc\u001b[49m\u001b[43m[\u001b[49m\u001b[43m[\u001b[49m\u001b[38;5;241;43m1\u001b[39;49m\u001b[43m]\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43m[\u001b[49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[38;5;124;43mNAME\u001b[39;49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[38;5;124;43mSKILL\u001b[39;49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[43m]\u001b[49m\u001b[43m]\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexing.py:961\u001b[0m, in \u001b[0;36m_LocationIndexer.__getitem__\u001b[1;34m(self, key)\u001b[0m\n\u001b[0;32m    959\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_is_scalar_access(key):\n\u001b[0;32m    960\u001b[0m         \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_get_value(\u001b[38;5;241m*\u001b[39mkey, takeable\u001b[38;5;241m=\u001b[39m\u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_takeable)\n\u001b[1;32m--> 961\u001b[0m     \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_getitem_tuple\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkey\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m    962\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n\u001b[0;32m    963\u001b[0m     \u001b[38;5;66;03m# we by definition only have the 0th axis\u001b[39;00m\n\u001b[0;32m    964\u001b[0m     axis \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39maxis \u001b[38;5;129;01mor\u001b[39;00m \u001b[38;5;241m0\u001b[39m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexing.py:1147\u001b[0m, in \u001b[0;36m_LocIndexer._getitem_tuple\u001b[1;34m(self, tup)\u001b[0m\n\u001b[0;32m   1145\u001b[0m \u001b[38;5;66;03m# ugly hack for GH #836\u001b[39;00m\n\u001b[0;32m   1146\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_multi_take_opportunity(tup):\n\u001b[1;32m-> 1147\u001b[0m     \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_multi_take\u001b[49m\u001b[43m(\u001b[49m\u001b[43mtup\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   1149\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_getitem_tuple_same_dim(tup)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexing.py:1098\u001b[0m, in \u001b[0;36m_LocIndexer._multi_take\u001b[1;34m(self, tup)\u001b[0m\n\u001b[0;32m   1082\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   1083\u001b[0m \u001b[38;5;124;03mCreate the indexers for the passed tuple of keys, and\u001b[39;00m\n\u001b[0;32m   1084\u001b[0m \u001b[38;5;124;03mexecutes the take operation. This allows the take operation to be\u001b[39;00m\n\u001b[1;32m   (...)\u001b[0m\n\u001b[0;32m   1095\u001b[0m \u001b[38;5;124;03mvalues: same type as the object being indexed\u001b[39;00m\n\u001b[0;32m   1096\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   1097\u001b[0m \u001b[38;5;66;03m# GH 836\u001b[39;00m\n\u001b[1;32m-> 1098\u001b[0m d \u001b[38;5;241m=\u001b[39m {\n\u001b[0;32m   1099\u001b[0m     axis: \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_get_listlike_indexer(key, axis)\n\u001b[0;32m   1100\u001b[0m     \u001b[38;5;28;01mfor\u001b[39;00m (key, axis) \u001b[38;5;129;01min\u001b[39;00m \u001b[38;5;28mzip\u001b[39m(tup, \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_AXIS_ORDERS)\n\u001b[0;32m   1101\u001b[0m }\n\u001b[0;32m   1102\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_reindex_with_indexers(d, copy\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mTrue\u001b[39;00m, allow_dups\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mTrue\u001b[39;00m)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexing.py:1099\u001b[0m, in \u001b[0;36m<dictcomp>\u001b[1;34m(.0)\u001b[0m\n\u001b[0;32m   1082\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   1083\u001b[0m \u001b[38;5;124;03mCreate the indexers for the passed tuple of keys, and\u001b[39;00m\n\u001b[0;32m   1084\u001b[0m \u001b[38;5;124;03mexecutes the take operation. This allows the take operation to be\u001b[39;00m\n\u001b[1;32m   (...)\u001b[0m\n\u001b[0;32m   1095\u001b[0m \u001b[38;5;124;03mvalues: same type as the object being indexed\u001b[39;00m\n\u001b[0;32m   1096\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   1097\u001b[0m \u001b[38;5;66;03m# GH 836\u001b[39;00m\n\u001b[0;32m   1098\u001b[0m d \u001b[38;5;241m=\u001b[39m {\n\u001b[1;32m-> 1099\u001b[0m     axis: \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_get_listlike_indexer\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkey\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43maxis\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   1100\u001b[0m     \u001b[38;5;28;01mfor\u001b[39;00m (key, axis) \u001b[38;5;129;01min\u001b[39;00m \u001b[38;5;28mzip\u001b[39m(tup, \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_AXIS_ORDERS)\n\u001b[0;32m   1101\u001b[0m }\n\u001b[0;32m   1102\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_reindex_with_indexers(d, copy\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mTrue\u001b[39;00m, allow_dups\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mTrue\u001b[39;00m)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexing.py:1327\u001b[0m, in \u001b[0;36m_LocIndexer._get_listlike_indexer\u001b[1;34m(self, key, axis)\u001b[0m\n\u001b[0;32m   1324\u001b[0m ax \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_get_axis(axis)\n\u001b[0;32m   1325\u001b[0m axis_name \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mobj\u001b[38;5;241m.\u001b[39m_get_axis_name(axis)\n\u001b[1;32m-> 1327\u001b[0m keyarr, indexer \u001b[38;5;241m=\u001b[39m \u001b[43max\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_get_indexer_strict\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkey\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43maxis_name\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   1329\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m keyarr, indexer\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:5782\u001b[0m, in \u001b[0;36mIndex._get_indexer_strict\u001b[1;34m(self, key, axis_name)\u001b[0m\n\u001b[0;32m   5779\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n\u001b[0;32m   5780\u001b[0m     keyarr, indexer, new_indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_reindex_non_unique(keyarr)\n\u001b[1;32m-> 5782\u001b[0m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_raise_if_missing\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkeyarr\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43mindexer\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43maxis_name\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   5784\u001b[0m keyarr \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mtake(indexer)\n\u001b[0;32m   5785\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28misinstance\u001b[39m(key, Index):\n\u001b[0;32m   5786\u001b[0m     \u001b[38;5;66;03m# GH 42790 - Preserve name from an Index\u001b[39;00m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:5842\u001b[0m, in \u001b[0;36mIndex._raise_if_missing\u001b[1;34m(self, key, indexer, axis_name)\u001b[0m\n\u001b[0;32m   5840\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m use_interval_msg:\n\u001b[0;32m   5841\u001b[0m         key \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mlist\u001b[39m(key)\n\u001b[1;32m-> 5842\u001b[0m     \u001b[38;5;28;01mraise\u001b[39;00m \u001b[38;5;167;01mKeyError\u001b[39;00m(\u001b[38;5;124mf\u001b[39m\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mNone of [\u001b[39m\u001b[38;5;132;01m{\u001b[39;00mkey\u001b[38;5;132;01m}\u001b[39;00m\u001b[38;5;124m] are in the [\u001b[39m\u001b[38;5;132;01m{\u001b[39;00maxis_name\u001b[38;5;132;01m}\u001b[39;00m\u001b[38;5;124m]\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n\u001b[0;32m   5844\u001b[0m not_found \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mlist\u001b[39m(ensure_index(key)[missing_mask\u001b[38;5;241m.\u001b[39mnonzero()[\u001b[38;5;241m0\u001b[39m]]\u001b[38;5;241m.\u001b[39munique())\n\u001b[0;32m   5845\u001b[0m \u001b[38;5;28;01mraise\u001b[39;00m \u001b[38;5;167;01mKeyError\u001b[39;00m(\u001b[38;5;124mf\u001b[39m\u001b[38;5;124m\"\u001b[39m\u001b[38;5;132;01m{\u001b[39;00mnot_found\u001b[38;5;132;01m}\u001b[39;00m\u001b[38;5;124m not in index\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n",
      "\u001b[1;31mKeyError\u001b[0m: \"None of [Int64Index([1], dtype='int64')] are in the [index]\""
     ]
    }
   ],
   "source": [
    "df2.loc[[1], [\"NAME\", \"SKILL\"]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "id": "008e8950",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>Unit Price</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>4-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>62</td>\n",
       "      <td>4.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>12-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Nick</td>\n",
       "      <td>Binder</td>\n",
       "      <td>29</td>\n",
       "      <td>1.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>21-Jul-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>55</td>\n",
       "      <td>12.49</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>29-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>81</td>\n",
       "      <td>19.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>7-Aug-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>42</td>\n",
       "      <td>23.95</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "     OrderDate   Region      Rep     Item  Units  Unit Price\n",
       "0   4-Jul-2014     East  Richard  Pen Set     62        4.99\n",
       "1  12-Jul-2014     East     Nick   Binder     29        1.99\n",
       "2  21-Jul-2014  Central   Morgan  Pen Set     55       12.49\n",
       "3  29-Jul-2014     East    Susan   Binder     81       19.99\n",
       "4   7-Aug-2014  Central  Matthew  Pen Set     42       23.95"
      ]
     },
     "execution_count": 86,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 87,
   "id": "7af5372f",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>23</th>\n",
       "      <td>15-Jan-2015</td>\n",
       "      <td>Central</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>30</th>\n",
       "      <td>15-Mar-2015</td>\n",
       "      <td>West</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      OrderDate   Region\n",
       "23  15-Jan-2015  Central\n",
       "30  15-Mar-2015     West"
      ]
     },
     "execution_count": 87,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.loc[[23,30],[\"OrderDate\", \"Region\"]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 88,
   "id": "2f3c2c3f",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 88,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 89,
   "id": "36c95335",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2.index = ['1st','2nd','3rd','4th','5th','6th',]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 90,
   "id": "0431891a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4th</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5th</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6th</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      ID     NAME SKILL\n",
       "1st  100     RAAM   WEB\n",
       "2nd  101    SHYAM  HTML\n",
       "3rd  102     SHIV   CSS\n",
       "4th  103  KRISHNA    JS\n",
       "5th  104    RADHA    PY\n",
       "6th  105    KANHA  JAVA"
      ]
     },
     "execution_count": 90,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 91,
   "id": "4849d3a5",
   "metadata": {},
   "outputs": [],
   "source": [
    "df2 = df2.reset_index(drop=True)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 92,
   "id": "a749c8cc",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 92,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 93,
   "id": "5963c9bb",
   "metadata": {},
   "outputs": [
    {
     "ename": "KeyError",
     "evalue": "\"['SKILL'] not found in axis\"",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mKeyError\u001b[0m                                  Traceback (most recent call last)",
      "Input \u001b[1;32mIn [93]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m \u001b[43mdf2\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mdrop\u001b[49m\u001b[43m(\u001b[49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[38;5;124;43mSKILL\u001b[39;49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[43m)\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\util\\_decorators.py:311\u001b[0m, in \u001b[0;36mdeprecate_nonkeyword_arguments.<locals>.decorate.<locals>.wrapper\u001b[1;34m(*args, **kwargs)\u001b[0m\n\u001b[0;32m    305\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mlen\u001b[39m(args) \u001b[38;5;241m>\u001b[39m num_allow_args:\n\u001b[0;32m    306\u001b[0m     warnings\u001b[38;5;241m.\u001b[39mwarn(\n\u001b[0;32m    307\u001b[0m         msg\u001b[38;5;241m.\u001b[39mformat(arguments\u001b[38;5;241m=\u001b[39marguments),\n\u001b[0;32m    308\u001b[0m         \u001b[38;5;167;01mFutureWarning\u001b[39;00m,\n\u001b[0;32m    309\u001b[0m         stacklevel\u001b[38;5;241m=\u001b[39mstacklevel,\n\u001b[0;32m    310\u001b[0m     )\n\u001b[1;32m--> 311\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m func(\u001b[38;5;241m*\u001b[39margs, \u001b[38;5;241m*\u001b[39m\u001b[38;5;241m*\u001b[39mkwargs)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\frame.py:4956\u001b[0m, in \u001b[0;36mDataFrame.drop\u001b[1;34m(self, labels, axis, index, columns, level, inplace, errors)\u001b[0m\n\u001b[0;32m   4808\u001b[0m \u001b[38;5;129m@deprecate_nonkeyword_arguments\u001b[39m(version\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mNone\u001b[39;00m, allowed_args\u001b[38;5;241m=\u001b[39m[\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mself\u001b[39m\u001b[38;5;124m\"\u001b[39m, \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mlabels\u001b[39m\u001b[38;5;124m\"\u001b[39m])\n\u001b[0;32m   4809\u001b[0m \u001b[38;5;28;01mdef\u001b[39;00m \u001b[38;5;21mdrop\u001b[39m(\n\u001b[0;32m   4810\u001b[0m     \u001b[38;5;28mself\u001b[39m,\n\u001b[1;32m   (...)\u001b[0m\n\u001b[0;32m   4817\u001b[0m     errors: \u001b[38;5;28mstr\u001b[39m \u001b[38;5;241m=\u001b[39m \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mraise\u001b[39m\u001b[38;5;124m\"\u001b[39m,\n\u001b[0;32m   4818\u001b[0m ):\n\u001b[0;32m   4819\u001b[0m     \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   4820\u001b[0m \u001b[38;5;124;03m    Drop specified labels from rows or columns.\u001b[39;00m\n\u001b[0;32m   4821\u001b[0m \n\u001b[1;32m   (...)\u001b[0m\n\u001b[0;32m   4954\u001b[0m \u001b[38;5;124;03m            weight  1.0     0.8\u001b[39;00m\n\u001b[0;32m   4955\u001b[0m \u001b[38;5;124;03m    \"\"\"\u001b[39;00m\n\u001b[1;32m-> 4956\u001b[0m     \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28;43msuper\u001b[39;49m\u001b[43m(\u001b[49m\u001b[43m)\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mdrop\u001b[49m\u001b[43m(\u001b[49m\n\u001b[0;32m   4957\u001b[0m \u001b[43m        \u001b[49m\u001b[43mlabels\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43mlabels\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4958\u001b[0m \u001b[43m        \u001b[49m\u001b[43maxis\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43maxis\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4959\u001b[0m \u001b[43m        \u001b[49m\u001b[43mindex\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43mindex\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4960\u001b[0m \u001b[43m        \u001b[49m\u001b[43mcolumns\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43mcolumns\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4961\u001b[0m \u001b[43m        \u001b[49m\u001b[43mlevel\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43mlevel\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4962\u001b[0m \u001b[43m        \u001b[49m\u001b[43minplace\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43minplace\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4963\u001b[0m \u001b[43m        \u001b[49m\u001b[43merrors\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43merrors\u001b[49m\u001b[43m,\u001b[49m\n\u001b[0;32m   4964\u001b[0m \u001b[43m    \u001b[49m\u001b[43m)\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\generic.py:4279\u001b[0m, in \u001b[0;36mNDFrame.drop\u001b[1;34m(self, labels, axis, index, columns, level, inplace, errors)\u001b[0m\n\u001b[0;32m   4277\u001b[0m \u001b[38;5;28;01mfor\u001b[39;00m axis, labels \u001b[38;5;129;01min\u001b[39;00m axes\u001b[38;5;241m.\u001b[39mitems():\n\u001b[0;32m   4278\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m labels \u001b[38;5;129;01mis\u001b[39;00m \u001b[38;5;129;01mnot\u001b[39;00m \u001b[38;5;28;01mNone\u001b[39;00m:\n\u001b[1;32m-> 4279\u001b[0m         obj \u001b[38;5;241m=\u001b[39m \u001b[43mobj\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_drop_axis\u001b[49m\u001b[43m(\u001b[49m\u001b[43mlabels\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43maxis\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43mlevel\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43mlevel\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43merrors\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43merrors\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   4281\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m inplace:\n\u001b[0;32m   4282\u001b[0m     \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_update_inplace(obj)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\generic.py:4323\u001b[0m, in \u001b[0;36mNDFrame._drop_axis\u001b[1;34m(self, labels, axis, level, errors, consolidate, only_slice)\u001b[0m\n\u001b[0;32m   4321\u001b[0m         new_axis \u001b[38;5;241m=\u001b[39m axis\u001b[38;5;241m.\u001b[39mdrop(labels, level\u001b[38;5;241m=\u001b[39mlevel, errors\u001b[38;5;241m=\u001b[39merrors)\n\u001b[0;32m   4322\u001b[0m     \u001b[38;5;28;01melse\u001b[39;00m:\n\u001b[1;32m-> 4323\u001b[0m         new_axis \u001b[38;5;241m=\u001b[39m \u001b[43maxis\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mdrop\u001b[49m\u001b[43m(\u001b[49m\u001b[43mlabels\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43merrors\u001b[49m\u001b[38;5;241;43m=\u001b[39;49m\u001b[43merrors\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   4324\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m axis\u001b[38;5;241m.\u001b[39mget_indexer(new_axis)\n\u001b[0;32m   4326\u001b[0m \u001b[38;5;66;03m# Case for non-unique axis\u001b[39;00m\n\u001b[0;32m   4327\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:6644\u001b[0m, in \u001b[0;36mIndex.drop\u001b[1;34m(self, labels, errors)\u001b[0m\n\u001b[0;32m   6642\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m mask\u001b[38;5;241m.\u001b[39many():\n\u001b[0;32m   6643\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m errors \u001b[38;5;241m!=\u001b[39m \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mignore\u001b[39m\u001b[38;5;124m\"\u001b[39m:\n\u001b[1;32m-> 6644\u001b[0m         \u001b[38;5;28;01mraise\u001b[39;00m \u001b[38;5;167;01mKeyError\u001b[39;00m(\u001b[38;5;124mf\u001b[39m\u001b[38;5;124m\"\u001b[39m\u001b[38;5;132;01m{\u001b[39;00m\u001b[38;5;28mlist\u001b[39m(labels[mask])\u001b[38;5;132;01m}\u001b[39;00m\u001b[38;5;124m not found in axis\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n\u001b[0;32m   6645\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m indexer[\u001b[38;5;241m~\u001b[39mmask]\n\u001b[0;32m   6646\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mdelete(indexer)\n",
      "\u001b[1;31mKeyError\u001b[0m: \"['SKILL'] not found in axis\""
     ]
    }
   ],
   "source": [
    "df2.drop('SKILL')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 94,
   "id": "b5636daa",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 94,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 95,
   "id": "d4b699f4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 95,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.reset_index(drop=True)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 96,
   "id": "e4a40f54",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>SKILL</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>WEB</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>HTML</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>CSS</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>JS</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>PY</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>JAVA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "  SKILL SKILL\n",
       "0   WEB   WEB\n",
       "1  HTML  HTML\n",
       "2   CSS   CSS\n",
       "3    JS    JS\n",
       "4    PY    PY\n",
       "5  JAVA  JAVA"
      ]
     },
     "execution_count": 96,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.iloc[:,[2,2]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 97,
   "id": "4580bf3a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "100    1\n",
       "101    1\n",
       "102    1\n",
       "103    1\n",
       "104    1\n",
       "105    1\n",
       "Name: ID, dtype: int64"
      ]
     },
     "execution_count": 97,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2['ID'].value_counts()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "id": "1a0f7e73",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'pandas.core.frame.DataFrame'>\n",
      "RangeIndex: 6 entries, 0 to 5\n",
      "Data columns (total 3 columns):\n",
      " #   Column  Non-Null Count  Dtype \n",
      "---  ------  --------------  ----- \n",
      " 0   ID      6 non-null      object\n",
      " 1   NAME    6 non-null      object\n",
      " 2   SKILL   6 non-null      object\n",
      "dtypes: object(3)\n",
      "memory usage: 272.0+ bytes\n"
     ]
    }
   ],
   "source": [
    "df2.info()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "73fb8a33",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 100,
   "id": "55d4bb71",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 100,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 101,
   "id": "32eb35fd",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "OrderDate  Region  Rep    Item   Units  Unit Price\n",
       "False      False   False  False  False  False         False\n",
       "dtype: bool"
      ]
     },
     "execution_count": 101,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.isnull().head().value_counts().notnull().isnull()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "id": "0c727558",
   "metadata": {},
   "outputs": [],
   "source": [
    "a = pd.DataFrame(np.random.rand(3,3), index=np.arange(3))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 103,
   "id": "0a7936c0",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>0.673104</td>\n",
       "      <td>0.806988</td>\n",
       "      <td>0.992174</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.375962</td>\n",
       "      <td>0.161285</td>\n",
       "      <td>0.205827</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.874974</td>\n",
       "      <td>0.337354</td>\n",
       "      <td>0.016282</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "          0         1         2\n",
       "0  0.673104  0.806988  0.992174\n",
       "1  0.375962  0.161285  0.205827\n",
       "2  0.874974  0.337354  0.016282"
      ]
     },
     "execution_count": 103,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 104,
   "id": "635689b9",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(3, 3)"
      ]
     },
     "execution_count": 104,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.shape"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 105,
   "id": "81c35fc4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0.37596215998879134"
      ]
     },
     "execution_count": 105,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a[0][1]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 106,
   "id": "bae4bf19",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>0.161285</td>\n",
       "      <td>0.205827</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>0.337354</td>\n",
       "      <td>0.016282</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "          1         2\n",
       "1  0.161285  0.205827\n",
       "2  0.337354  0.016282"
      ]
     },
     "execution_count": 106,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.iloc[[1,2],[1,2]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 107,
   "id": "ad8611e5",
   "metadata": {},
   "outputs": [],
   "source": [
    "a.index = [\"1st\",\"3rd\",\"2nd\"]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 108,
   "id": "195096c4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>1st</th>\n",
       "      <td>0.673104</td>\n",
       "      <td>0.806988</td>\n",
       "      <td>0.992174</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>0.375962</td>\n",
       "      <td>0.161285</td>\n",
       "      <td>0.205827</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>0.874974</td>\n",
       "      <td>0.337354</td>\n",
       "      <td>0.016282</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "            0         1         2\n",
       "1st  0.673104  0.806988  0.992174\n",
       "3rd  0.375962  0.161285  0.205827\n",
       "2nd  0.874974  0.337354  0.016282"
      ]
     },
     "execution_count": 108,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 109,
   "id": "f4a81619",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>3rd</th>\n",
       "      <td>0.161285</td>\n",
       "      <td>0.205827</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2nd</th>\n",
       "      <td>0.337354</td>\n",
       "      <td>0.016282</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "            1         2\n",
       "3rd  0.161285  0.205827\n",
       "2nd  0.337354  0.016282"
      ]
     },
     "execution_count": 109,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.iloc[[1,2],[1,2]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 110,
   "id": "9d306725",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>0</th>\n",
       "      <th>1</th>\n",
       "      <th>2</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>count</th>\n",
       "      <td>3.000000</td>\n",
       "      <td>3.000000</td>\n",
       "      <td>3.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>mean</th>\n",
       "      <td>0.641346</td>\n",
       "      <td>0.435209</td>\n",
       "      <td>0.404761</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>std</th>\n",
       "      <td>0.251017</td>\n",
       "      <td>0.333789</td>\n",
       "      <td>0.517467</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>min</th>\n",
       "      <td>0.375962</td>\n",
       "      <td>0.161285</td>\n",
       "      <td>0.016282</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>25%</th>\n",
       "      <td>0.524533</td>\n",
       "      <td>0.249320</td>\n",
       "      <td>0.111054</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>50%</th>\n",
       "      <td>0.673104</td>\n",
       "      <td>0.337354</td>\n",
       "      <td>0.205827</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>75%</th>\n",
       "      <td>0.774039</td>\n",
       "      <td>0.572171</td>\n",
       "      <td>0.599000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>max</th>\n",
       "      <td>0.874974</td>\n",
       "      <td>0.806988</td>\n",
       "      <td>0.992174</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "              0         1         2\n",
       "count  3.000000  3.000000  3.000000\n",
       "mean   0.641346  0.435209  0.404761\n",
       "std    0.251017  0.333789  0.517467\n",
       "min    0.375962  0.161285  0.016282\n",
       "25%    0.524533  0.249320  0.111054\n",
       "50%    0.673104  0.337354  0.205827\n",
       "75%    0.774039  0.572171  0.599000\n",
       "max    0.874974  0.806988  0.992174"
      ]
     },
     "execution_count": 110,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.describe()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 111,
   "id": "561e373b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0         1         2       \n",
       "0.375962  0.161285  0.205827    1\n",
       "0.673104  0.806988  0.992174    1\n",
       "0.874974  0.337354  0.016282    1\n",
       "dtype: int64"
      ]
     },
     "execution_count": 111,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.value_counts()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 112,
   "id": "deab053a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 112,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 113,
   "id": "4e5754e4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 113,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 200,
   "id": "e3b227c3",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME\n",
       "0  100     RAAM\n",
       "1  101    SHYAM\n",
       "2  102     SHIV\n",
       "3  103  KRISHNA\n",
       "4  104    RADHA\n",
       "5  105    KANHA"
      ]
     },
     "execution_count": 200,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2.drop(columns=['SKILL'], axis=1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 120,
   "id": "902dfdcd",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>NAME</th>\n",
       "      <th>SKILL</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>100</td>\n",
       "      <td>RAAM</td>\n",
       "      <td>WEB</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>101</td>\n",
       "      <td>SHYAM</td>\n",
       "      <td>HTML</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>102</td>\n",
       "      <td>SHIV</td>\n",
       "      <td>CSS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>103</td>\n",
       "      <td>KRISHNA</td>\n",
       "      <td>JS</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>104</td>\n",
       "      <td>RADHA</td>\n",
       "      <td>PY</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>105</td>\n",
       "      <td>KANHA</td>\n",
       "      <td>JAVA</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "    ID     NAME SKILL\n",
       "0  100     RAAM   WEB\n",
       "1  101    SHYAM  HTML\n",
       "2  102     SHIV   CSS\n",
       "3  103  KRISHNA    JS\n",
       "4  104    RADHA    PY\n",
       "5  105    KANHA  JAVA"
      ]
     },
     "execution_count": 120,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 161,
   "id": "97c678f2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>UnitPrice</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>4-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>62</td>\n",
       "      <td>4.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>12-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Nick</td>\n",
       "      <td>Binder</td>\n",
       "      <td>29</td>\n",
       "      <td>1.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>21-Jul-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>55</td>\n",
       "      <td>12.49</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>29-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>81</td>\n",
       "      <td>19.99</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>7-Aug-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>42</td>\n",
       "      <td>23.95</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "     OrderDate   Region      Rep     Item  Units  UnitPrice\n",
       "0   4-Jul-2014     East  Richard  Pen Set     62       4.99\n",
       "1  12-Jul-2014     East     Nick   Binder     29       1.99\n",
       "2  21-Jul-2014  Central   Morgan  Pen Set     55      12.49\n",
       "3  29-Jul-2014     East    Susan   Binder     81      19.99\n",
       "4   7-Aug-2014  Central  Matthew  Pen Set     42      23.95"
      ]
     },
     "execution_count": 161,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 163,
   "id": "c7caae4b",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.columns = ['OrderDate', 'Region', 'Rep', 'Item', 'Units', 'UnitPrice']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 147,
   "id": "f1ad1206",
   "metadata": {},
   "outputs": [],
   "source": [
    "Binder_Sale = df.loc[1,[\"Units\"]]*df.loc[1,[\"Unit Price\"]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 171,
   "id": "8354545a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0     309.38\n",
       "1      57.71\n",
       "2     686.95\n",
       "3    1619.19\n",
       "4    1005.90\n",
       "dtype: float64"
      ]
     },
     "execution_count": 171,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "Sale = df.Units*df.UnitPrice\n",
    "Sale.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 169,
   "id": "535433ee",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "309.38"
      ]
     },
     "execution_count": 169,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "Sale.loc[0]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 173,
   "id": "61b7d19a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "('Sale of Binder is', 57.71)"
      ]
     },
     "execution_count": 173,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"Sale of Binder is\", Sale.loc[1]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 175,
   "id": "0d84b9b9",
   "metadata": {},
   "outputs": [],
   "source": [
    "df['Sale'] = Sale\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 178,
   "id": "47c0424d",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.to_csv(\"Sale.csv\", index=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 181,
   "id": "6eb8e7fc",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>UnitPrice</th>\n",
       "      <th>Sale</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>4-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>62</td>\n",
       "      <td>4.99</td>\n",
       "      <td>309.38</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>12-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Nick</td>\n",
       "      <td>Binder</td>\n",
       "      <td>29</td>\n",
       "      <td>1.99</td>\n",
       "      <td>57.71</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>21-Jul-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>55</td>\n",
       "      <td>12.49</td>\n",
       "      <td>686.95</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>29-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>81</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1619.19</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>7-Aug-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>42</td>\n",
       "      <td>23.95</td>\n",
       "      <td>1005.90</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>5</th>\n",
       "      <td>15-Aug-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>35</td>\n",
       "      <td>4.99</td>\n",
       "      <td>174.65</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>6</th>\n",
       "      <td>24-Aug-2014</td>\n",
       "      <td>West</td>\n",
       "      <td>James</td>\n",
       "      <td>Desk</td>\n",
       "      <td>3</td>\n",
       "      <td>275.00</td>\n",
       "      <td>825.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>7</th>\n",
       "      <td>1-Sep-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Smith</td>\n",
       "      <td>Desk</td>\n",
       "      <td>2</td>\n",
       "      <td>125.00</td>\n",
       "      <td>250.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>8</th>\n",
       "      <td>10-Sep-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>7</td>\n",
       "      <td>1.29</td>\n",
       "      <td>9.03</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>9</th>\n",
       "      <td>18-Sep-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>16</td>\n",
       "      <td>15.99</td>\n",
       "      <td>255.84</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>10</th>\n",
       "      <td>27-Sep-2014</td>\n",
       "      <td>West</td>\n",
       "      <td>James</td>\n",
       "      <td>Pen</td>\n",
       "      <td>76</td>\n",
       "      <td>1.99</td>\n",
       "      <td>151.24</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>11</th>\n",
       "      <td>5-Oct-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>28</td>\n",
       "      <td>8.99</td>\n",
       "      <td>251.72</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>12</th>\n",
       "      <td>14-Oct-2014</td>\n",
       "      <td>West</td>\n",
       "      <td>Thomas</td>\n",
       "      <td>Binder</td>\n",
       "      <td>57</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1139.43</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>13</th>\n",
       "      <td>22-Oct-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pen</td>\n",
       "      <td>64</td>\n",
       "      <td>8.99</td>\n",
       "      <td>575.36</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>14</th>\n",
       "      <td>31-Oct-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Rachel</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>14</td>\n",
       "      <td>1.29</td>\n",
       "      <td>18.06</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>15</th>\n",
       "      <td>8-Nov-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Pen</td>\n",
       "      <td>15</td>\n",
       "      <td>19.99</td>\n",
       "      <td>299.85</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>16</th>\n",
       "      <td>17-Nov-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Binder</td>\n",
       "      <td>11</td>\n",
       "      <td>4.99</td>\n",
       "      <td>54.89</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>17</th>\n",
       "      <td>25-Nov-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>96</td>\n",
       "      <td>4.99</td>\n",
       "      <td>479.04</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>18</th>\n",
       "      <td>4-Dec-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Binder</td>\n",
       "      <td>94</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1879.06</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>19</th>\n",
       "      <td>12-Dec-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Smith</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>67</td>\n",
       "      <td>1.29</td>\n",
       "      <td>86.43</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>20</th>\n",
       "      <td>21-Dec-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Rachel</td>\n",
       "      <td>Binder</td>\n",
       "      <td>28</td>\n",
       "      <td>4.99</td>\n",
       "      <td>139.72</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>21</th>\n",
       "      <td>29-Dec-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>74</td>\n",
       "      <td>15.99</td>\n",
       "      <td>1183.26</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>22</th>\n",
       "      <td>6-Jan-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>95</td>\n",
       "      <td>1.99</td>\n",
       "      <td>189.05</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>23</th>\n",
       "      <td>15-Jan-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Binder</td>\n",
       "      <td>46</td>\n",
       "      <td>8.99</td>\n",
       "      <td>413.54</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>24</th>\n",
       "      <td>23-Jan-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Binder</td>\n",
       "      <td>50</td>\n",
       "      <td>19.99</td>\n",
       "      <td>999.50</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>25</th>\n",
       "      <td>1-Feb-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Smith</td>\n",
       "      <td>Binder</td>\n",
       "      <td>87</td>\n",
       "      <td>15.00</td>\n",
       "      <td>1305.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>26</th>\n",
       "      <td>9-Feb-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>36</td>\n",
       "      <td>4.99</td>\n",
       "      <td>179.64</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>27</th>\n",
       "      <td>18-Feb-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Binder</td>\n",
       "      <td>4</td>\n",
       "      <td>4.99</td>\n",
       "      <td>19.96</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>28</th>\n",
       "      <td>26-Feb-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Pen</td>\n",
       "      <td>27</td>\n",
       "      <td>19.99</td>\n",
       "      <td>539.73</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>29</th>\n",
       "      <td>7-Mar-2015</td>\n",
       "      <td>West</td>\n",
       "      <td>James</td>\n",
       "      <td>Binder</td>\n",
       "      <td>7</td>\n",
       "      <td>19.99</td>\n",
       "      <td>139.93</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>30</th>\n",
       "      <td>15-Mar-2015</td>\n",
       "      <td>West</td>\n",
       "      <td>James</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>56</td>\n",
       "      <td>2.99</td>\n",
       "      <td>167.44</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>31</th>\n",
       "      <td>24-Mar-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>50</td>\n",
       "      <td>4.99</td>\n",
       "      <td>249.50</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>32</th>\n",
       "      <td>1-Apr-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Binder</td>\n",
       "      <td>60</td>\n",
       "      <td>4.99</td>\n",
       "      <td>299.40</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>33</th>\n",
       "      <td>10-Apr-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Rachel</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>66</td>\n",
       "      <td>1.99</td>\n",
       "      <td>131.34</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>34</th>\n",
       "      <td>18-Apr-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Rachel</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>75</td>\n",
       "      <td>1.99</td>\n",
       "      <td>149.25</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>35</th>\n",
       "      <td>27-Apr-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Nick</td>\n",
       "      <td>Pen</td>\n",
       "      <td>96</td>\n",
       "      <td>4.99</td>\n",
       "      <td>479.04</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>36</th>\n",
       "      <td>5-May-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>90</td>\n",
       "      <td>4.99</td>\n",
       "      <td>449.10</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>37</th>\n",
       "      <td>14-May-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>53</td>\n",
       "      <td>1.29</td>\n",
       "      <td>68.37</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>38</th>\n",
       "      <td>22-May-2015</td>\n",
       "      <td>West</td>\n",
       "      <td>Thomas</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>32</td>\n",
       "      <td>1.99</td>\n",
       "      <td>63.68</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>39</th>\n",
       "      <td>31-May-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Bill</td>\n",
       "      <td>Binder</td>\n",
       "      <td>80</td>\n",
       "      <td>8.99</td>\n",
       "      <td>719.20</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>40</th>\n",
       "      <td>8-Jun-2015</td>\n",
       "      <td>East</td>\n",
       "      <td>Richard</td>\n",
       "      <td>Binder</td>\n",
       "      <td>60</td>\n",
       "      <td>8.99</td>\n",
       "      <td>539.40</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>41</th>\n",
       "      <td>17-Jun-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Desk</td>\n",
       "      <td>5</td>\n",
       "      <td>125.00</td>\n",
       "      <td>625.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>42</th>\n",
       "      <td>25-Jun-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Morgan</td>\n",
       "      <td>Pencil</td>\n",
       "      <td>90</td>\n",
       "      <td>4.99</td>\n",
       "      <td>449.10</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      OrderDate   Region      Rep     Item  Units  UnitPrice     Sale\n",
       "0    4-Jul-2014     East  Richard  Pen Set     62       4.99   309.38\n",
       "1   12-Jul-2014     East     Nick   Binder     29       1.99    57.71\n",
       "2   21-Jul-2014  Central   Morgan  Pen Set     55      12.49   686.95\n",
       "3   29-Jul-2014     East    Susan   Binder     81      19.99  1619.19\n",
       "4    7-Aug-2014  Central  Matthew  Pen Set     42      23.95  1005.90\n",
       "5   15-Aug-2014     East  Richard   Pencil     35       4.99   174.65\n",
       "6   24-Aug-2014     West    James     Desk      3     275.00   825.00\n",
       "7    1-Sep-2014  Central    Smith     Desk      2     125.00   250.00\n",
       "8   10-Sep-2014  Central     Bill   Pencil      7       1.29     9.03\n",
       "9   18-Sep-2014     East  Richard  Pen Set     16      15.99   255.84\n",
       "10  27-Sep-2014     West    James      Pen     76       1.99   151.24\n",
       "11   5-Oct-2014  Central   Morgan   Binder     28       8.99   251.72\n",
       "12  14-Oct-2014     West   Thomas   Binder     57      19.99  1139.43\n",
       "13  22-Oct-2014     East  Richard      Pen     64       8.99   575.36\n",
       "14  31-Oct-2014  Central   Rachel   Pencil     14       1.29    18.06\n",
       "15   8-Nov-2014     East    Susan      Pen     15      19.99   299.85\n",
       "16  17-Nov-2014  Central     Alex   Binder     11       4.99    54.89\n",
       "17  25-Nov-2014  Central  Matthew  Pen Set     96       4.99   479.04\n",
       "18   4-Dec-2014  Central     Alex   Binder     94      19.99  1879.06\n",
       "19  12-Dec-2014  Central    Smith   Pencil     67       1.29    86.43\n",
       "20  21-Dec-2014  Central   Rachel   Binder     28       4.99   139.72\n",
       "21  29-Dec-2014     East    Susan  Pen Set     74      15.99  1183.26\n",
       "22   6-Jan-2015     East  Richard   Pencil     95       1.99   189.05\n",
       "23  15-Jan-2015  Central     Bill   Binder     46       8.99   413.54\n",
       "24  23-Jan-2015  Central  Matthew   Binder     50      19.99   999.50\n",
       "25   1-Feb-2015  Central    Smith   Binder     87      15.00  1305.00\n",
       "26   9-Feb-2015  Central     Alex   Pencil     36       4.99   179.64\n",
       "27  18-Feb-2015     East  Richard   Binder      4       4.99    19.96\n",
       "28  26-Feb-2015  Central     Bill      Pen     27      19.99   539.73\n",
       "29   7-Mar-2015     West    James   Binder      7      19.99   139.93\n",
       "30  15-Mar-2015     West    James   Pencil     56       2.99   167.44\n",
       "31  24-Mar-2015  Central     Alex  Pen Set     50       4.99   249.50\n",
       "32   1-Apr-2015     East  Richard   Binder     60       4.99   299.40\n",
       "33  10-Apr-2015  Central   Rachel   Pencil     66       1.99   131.34\n",
       "34  18-Apr-2015  Central   Rachel   Pencil     75       1.99   149.25\n",
       "35  27-Apr-2015     East     Nick      Pen     96       4.99   479.04\n",
       "36   5-May-2015  Central     Alex   Pencil     90       4.99   449.10\n",
       "37  14-May-2015  Central     Bill   Pencil     53       1.29    68.37\n",
       "38  22-May-2015     West   Thomas   Pencil     32       1.99    63.68\n",
       "39  31-May-2015  Central     Bill   Binder     80       8.99   719.20\n",
       "40   8-Jun-2015     East  Richard   Binder     60       8.99   539.40\n",
       "41  17-Jun-2015  Central  Matthew     Desk      5     125.00   625.00\n",
       "42  25-Jun-2015  Central   Morgan   Pencil     90       4.99   449.10"
      ]
     },
     "execution_count": 181,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "pd.read_csv(\"Sale.csv\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 182,
   "id": "a01e98b4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "19627.879999999997"
      ]
     },
     "execution_count": 182,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df.Sale.sum()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 198,
   "id": "1745bf07",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>OrderDate</th>\n",
       "      <th>Region</th>\n",
       "      <th>Rep</th>\n",
       "      <th>Item</th>\n",
       "      <th>Units</th>\n",
       "      <th>UnitPrice</th>\n",
       "      <th>Sale</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>18</th>\n",
       "      <td>4-Dec-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Alex</td>\n",
       "      <td>Binder</td>\n",
       "      <td>94</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1879.06</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>29-Jul-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Binder</td>\n",
       "      <td>81</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1619.19</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>25</th>\n",
       "      <td>1-Feb-2015</td>\n",
       "      <td>Central</td>\n",
       "      <td>Smith</td>\n",
       "      <td>Binder</td>\n",
       "      <td>87</td>\n",
       "      <td>15.00</td>\n",
       "      <td>1305.00</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>21</th>\n",
       "      <td>29-Dec-2014</td>\n",
       "      <td>East</td>\n",
       "      <td>Susan</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>74</td>\n",
       "      <td>15.99</td>\n",
       "      <td>1183.26</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>12</th>\n",
       "      <td>14-Oct-2014</td>\n",
       "      <td>West</td>\n",
       "      <td>Thomas</td>\n",
       "      <td>Binder</td>\n",
       "      <td>57</td>\n",
       "      <td>19.99</td>\n",
       "      <td>1139.43</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>7-Aug-2014</td>\n",
       "      <td>Central</td>\n",
       "      <td>Matthew</td>\n",
       "      <td>Pen Set</td>\n",
       "      <td>42</td>\n",
       "      <td>23.95</td>\n",
       "      <td>1005.90</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "      OrderDate   Region      Rep     Item  Units  UnitPrice     Sale\n",
       "18   4-Dec-2014  Central     Alex   Binder     94      19.99  1879.06\n",
       "3   29-Jul-2014     East    Susan   Binder     81      19.99  1619.19\n",
       "25   1-Feb-2015  Central    Smith   Binder     87      15.00  1305.00\n",
       "21  29-Dec-2014     East    Susan  Pen Set     74      15.99  1183.26\n",
       "12  14-Oct-2014     West   Thomas   Binder     57      19.99  1139.43\n",
       "4    7-Aug-2014  Central  Matthew  Pen Set     42      23.95  1005.90"
      ]
     },
     "execution_count": 198,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "df[df.Sale>1000].sort_values('Sale', ascending=False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 203,
   "id": "2e6435db",
   "metadata": {},
   "outputs": [
    {
     "name": "stderr",
     "output_type": "stream",
     "text": [
      "C:\\Users\\laksh\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\common.py:241: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.\n",
      "  result = np.asarray(values, dtype=dtype)\n"
     ]
    },
    {
     "ename": "TypeError",
     "evalue": "unhashable type: 'DataFrame'",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
      "Input \u001b[1;32mIn [203]\u001b[0m, in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[0m \u001b[43mdf\u001b[49m\u001b[43m[\u001b[49m\u001b[43mdf\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mgroupby\u001b[49m\u001b[43m(\u001b[49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[38;5;124;43mItem\u001b[39;49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[43m)\u001b[49m\u001b[43m]\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\frame.py:3512\u001b[0m, in \u001b[0;36mDataFrame.__getitem__\u001b[1;34m(self, key)\u001b[0m\n\u001b[0;32m   3510\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m is_iterator(key):\n\u001b[0;32m   3511\u001b[0m         key \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mlist\u001b[39m(key)\n\u001b[1;32m-> 3512\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mcolumns\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_get_indexer_strict\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkey\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[38;5;124;43mcolumns\u001b[39;49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[43m)\u001b[49m[\u001b[38;5;241m1\u001b[39m]\n\u001b[0;32m   3514\u001b[0m \u001b[38;5;66;03m# take() does not accept boolean indexers\u001b[39;00m\n\u001b[0;32m   3515\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mgetattr\u001b[39m(indexer, \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mdtype\u001b[39m\u001b[38;5;124m\"\u001b[39m, \u001b[38;5;28;01mNone\u001b[39;00m) \u001b[38;5;241m==\u001b[39m \u001b[38;5;28mbool\u001b[39m:\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:5777\u001b[0m, in \u001b[0;36mIndex._get_indexer_strict\u001b[1;34m(self, key, axis_name)\u001b[0m\n\u001b[0;32m   5774\u001b[0m     keyarr \u001b[38;5;241m=\u001b[39m com\u001b[38;5;241m.\u001b[39masarray_tuplesafe(keyarr)\n\u001b[0;32m   5776\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_index_as_unique:\n\u001b[1;32m-> 5777\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mget_indexer_for\u001b[49m\u001b[43m(\u001b[49m\u001b[43mkeyarr\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   5778\u001b[0m     keyarr \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mreindex(keyarr)[\u001b[38;5;241m0\u001b[39m]\n\u001b[0;32m   5779\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:5764\u001b[0m, in \u001b[0;36mIndex.get_indexer_for\u001b[1;34m(self, target)\u001b[0m\n\u001b[0;32m   5746\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   5747\u001b[0m \u001b[38;5;124;03mGuaranteed return of an indexer even when non-unique.\u001b[39;00m\n\u001b[0;32m   5748\u001b[0m \n\u001b[1;32m   (...)\u001b[0m\n\u001b[0;32m   5761\u001b[0m \u001b[38;5;124;03marray([0, 2])\u001b[39;00m\n\u001b[0;32m   5762\u001b[0m \u001b[38;5;124;03m\"\"\"\u001b[39;00m\n\u001b[0;32m   5763\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_index_as_unique:\n\u001b[1;32m-> 5764\u001b[0m     \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mget_indexer\u001b[49m\u001b[43m(\u001b[49m\u001b[43mtarget\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   5765\u001b[0m indexer, _ \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mget_indexer_non_unique(target)\n\u001b[0;32m   5766\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m indexer\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:3784\u001b[0m, in \u001b[0;36mIndex.get_indexer\u001b[1;34m(self, target, method, limit, tolerance)\u001b[0m\n\u001b[0;32m   3779\u001b[0m     target \u001b[38;5;241m=\u001b[39m target\u001b[38;5;241m.\u001b[39mastype(dtype, copy\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;01mFalse\u001b[39;00m)\n\u001b[0;32m   3780\u001b[0m     \u001b[38;5;28;01mreturn\u001b[39;00m this\u001b[38;5;241m.\u001b[39m_get_indexer(\n\u001b[0;32m   3781\u001b[0m         target, method\u001b[38;5;241m=\u001b[39mmethod, limit\u001b[38;5;241m=\u001b[39mlimit, tolerance\u001b[38;5;241m=\u001b[39mtolerance\n\u001b[0;32m   3782\u001b[0m     )\n\u001b[1;32m-> 3784\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_get_indexer\u001b[49m\u001b[43m(\u001b[49m\u001b[43mtarget\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43mmethod\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43mlimit\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43mtolerance\u001b[49m\u001b[43m)\u001b[49m\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\core\\indexes\\base.py:3809\u001b[0m, in \u001b[0;36mIndex._get_indexer\u001b[1;34m(self, target, method, limit, tolerance)\u001b[0m\n\u001b[0;32m   3804\u001b[0m         \u001b[38;5;66;03m# error: \"IndexEngine\" has no attribute \"_extract_level_codes\"\u001b[39;00m\n\u001b[0;32m   3805\u001b[0m         tgt_values \u001b[38;5;241m=\u001b[39m engine\u001b[38;5;241m.\u001b[39m_extract_level_codes(  \u001b[38;5;66;03m# type: ignore[attr-defined]\u001b[39;00m\n\u001b[0;32m   3806\u001b[0m             target\n\u001b[0;32m   3807\u001b[0m         )\n\u001b[1;32m-> 3809\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28;43mself\u001b[39;49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43m_engine\u001b[49m\u001b[38;5;241;43m.\u001b[39;49m\u001b[43mget_indexer\u001b[49m\u001b[43m(\u001b[49m\u001b[43mtgt_values\u001b[49m\u001b[43m)\u001b[49m\n\u001b[0;32m   3811\u001b[0m \u001b[38;5;28;01mreturn\u001b[39;00m ensure_platform_int(indexer)\n",
      "File \u001b[1;32m~\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\pandas\\_libs\\index.pyx:305\u001b[0m, in \u001b[0;36mpandas._libs.index.IndexEngine.get_indexer\u001b[1;34m()\u001b[0m\n",
      "File \u001b[1;32mpandas\\_libs\\hashtable_class_helper.pxi:5247\u001b[0m, in \u001b[0;36mpandas._libs.hashtable.PyObjectHashTable.lookup\u001b[1;34m()\u001b[0m\n",
      "\u001b[1;31mTypeError\u001b[0m: unhashable type: 'DataFrame'"
     ]
    }
   ],
   "source": [
    "df[df.groupby('Item')]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 204,
   "id": "c8deb196",
   "metadata": {},
   "outputs": [],
   "source": [
    "sal = pd.read_csv(\"Salary Dataset.csv\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 205,
   "id": "4b836cb4",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>Company Name</th>\n",
       "      <th>Job Title</th>\n",
       "      <th>Salaries Reported</th>\n",
       "      <th>Location</th>\n",
       "      <th>Salary</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>Mu Sigma</td>\n",
       "      <td>Data Scientist</td>\n",
       "      <td>105.0</td>\n",
       "      <td>Bangalore</td>\n",
       "      <td>₹6,48,573/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>IBM</td>\n",
       "      <td>Data Scientist</td>\n",
       "      <td>95.0</td>\n",
       "      <td>Bangalore</td>\n",
       "      <td>₹11,91,950/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>Tata Consultancy Services</td>\n",
       "      <td>Data Scientist</td>\n",
       "      <td>66.0</td>\n",
       "      <td>Bangalore</td>\n",
       "      <td>₹8,36,874/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>Impact Analytics</td>\n",
       "      <td>Data Scientist</td>\n",
       "      <td>40.0</td>\n",
       "      <td>Bangalore</td>\n",
       "      <td>₹6,69,578/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>Accenture</td>\n",
       "      <td>Data Scientist</td>\n",
       "      <td>32.0</td>\n",
       "      <td>Bangalore</td>\n",
       "      <td>₹9,44,110/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>...</th>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "      <td>...</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4339</th>\n",
       "      <td>TaiyōAI</td>\n",
       "      <td>Machine Learning Scientist</td>\n",
       "      <td>1.0</td>\n",
       "      <td>Mumbai</td>\n",
       "      <td>₹5,180/mo</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4340</th>\n",
       "      <td>Decimal Point Analytics</td>\n",
       "      <td>Machine Learning Developer</td>\n",
       "      <td>1.0</td>\n",
       "      <td>Mumbai</td>\n",
       "      <td>₹7,51,286/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4341</th>\n",
       "      <td>MyWays</td>\n",
       "      <td>Machine Learning Developer</td>\n",
       "      <td>1.0</td>\n",
       "      <td>Mumbai</td>\n",
       "      <td>₹4,10,952/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4342</th>\n",
       "      <td>Market Pulse Technologies</td>\n",
       "      <td>Software Engineer - Machine Learning</td>\n",
       "      <td>1.0</td>\n",
       "      <td>Mumbai</td>\n",
       "      <td>₹16,12,324/yr</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4343</th>\n",
       "      <td>vPhrase</td>\n",
       "      <td>Machine Learning Engineer</td>\n",
       "      <td>1.0</td>\n",
       "      <td>Mumbai</td>\n",
       "      <td>₹9,39,843/yr</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "<p>4344 rows × 5 columns</p>\n",
       "</div>"
      ],
      "text/plain": [
       "                   Company Name                             Job Title  \\\n",
       "0                      Mu Sigma                        Data Scientist   \n",
       "1                           IBM                        Data Scientist   \n",
       "2     Tata Consultancy Services                        Data Scientist   \n",
       "3              Impact Analytics                        Data Scientist   \n",
       "4                     Accenture                        Data Scientist   \n",
       "...                         ...                                   ...   \n",
       "4339                    TaiyōAI            Machine Learning Scientist   \n",
       "4340    Decimal Point Analytics            Machine Learning Developer   \n",
       "4341                     MyWays            Machine Learning Developer   \n",
       "4342  Market Pulse Technologies  Software Engineer - Machine Learning   \n",
       "4343                    vPhrase             Machine Learning Engineer   \n",
       "\n",
       "      Salaries Reported   Location         Salary  \n",
       "0                 105.0  Bangalore   ₹6,48,573/yr  \n",
       "1                  95.0  Bangalore  ₹11,91,950/yr  \n",
       "2                  66.0  Bangalore   ₹8,36,874/yr  \n",
       "3                  40.0  Bangalore   ₹6,69,578/yr  \n",
       "4                  32.0  Bangalore   ₹9,44,110/yr  \n",
       "...                 ...        ...            ...  \n",
       "4339                1.0     Mumbai      ₹5,180/mo  \n",
       "4340                1.0     Mumbai   ₹7,51,286/yr  \n",
       "4341                1.0     Mumbai   ₹4,10,952/yr  \n",
       "4342                1.0     Mumbai  ₹16,12,324/yr  \n",
       "4343                1.0     Mumbai   ₹9,39,843/yr  \n",
       "\n",
       "[4344 rows x 5 columns]"
      ]
     },
     "execution_count": 205,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sal"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 211,
   "id": "f7725df5",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "21720"
      ]
     },
     "execution_count": 211,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sal.size"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "d11397b9",
   "metadata": {},
   "outputs": [],
   "source": [
    "sal.jobtitle"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.2"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
