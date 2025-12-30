# -orenci.not.takip.uygulaması-
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "25d4dfe5-b418-4df7-8d90-84f50fbdbf61",
   "metadata": {},
   "outputs": [],
   "source": [
    "#student_grade_app.py"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "id": "2a7be95b-f78f-4cb8-975c-c3bed6dbb4a8",
   "metadata": {},
   "outputs": [],
   "source": [
    "Dersler=\"matematik\",\"fizik\",\"kimya\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 50,
   "id": "526eeddf-7159-4552-a22e-2488b31a0391",
   "metadata": {},
   "outputs": [],
   "source": [
    "Öğrenciler = \"Ece\",\"Eda\",\"Ali\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 51,
   "id": "920911d8-fd3b-4a53-995c-763b64b75a22",
   "metadata": {},
   "outputs": [],
   "source": [
    "Bölümler = \"makine\",\"yazılım\",\"elektrik\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 53,
   "id": "b86d903f-4ff0-48aa-8845-5d324de65528",
   "metadata": {},
   "outputs": [],
   "source": [
    "Numaralar = \"12\",\"13\",\"14\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 59,
   "id": "9fe0d015-163d-42ef-bd81-0f3dcc1dd9e9",
   "metadata": {},
   "outputs": [],
   "source": [
    "VizeSonuçları = \"75\",\"80\",\"85\",\"90\",\"95\",\"100\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "id": "68659e25-f8c2-43ce-a53c-18c0e7061e1e",
   "metadata": {},
   "outputs": [],
   "source": [
    "FinalSonuçları = \"50\",\"55\",\"60\",\"65\",\"70\",\"75\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 74,
   "id": "73861e15-32d4-4204-8f66-70f925e6c175",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "('Ece', 'makine', '12')"
      ]
     },
     "execution_count": 74,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "Öğrenciler[:1:] + Bölümler[:1:1] + Numaralar[:1:]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 78,
   "id": "1cf6e966-49de-4bf3-9042-e9f40885848c",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "('Eda', 'elektrik', '13')"
      ]
     },
     "execution_count": 78,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "Öğrenciler[1:2:] + Bölümler[2:3:] + Numaralar[1:2:]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 84,
   "id": "17528163-4247-42a0-833a-c2e5459417a2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "('Ali', 'yazılım', '14')"
      ]
     },
     "execution_count": 84,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "Öğrenciler[2:3:] + Bölümler[1:2:] + Numaralar[2:3:]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 85,
   "id": "47c5914a-6d0b-468a-bc7f-6c2c35fb8d6e",
   "metadata": {},
   "outputs": [],
   "source": [
    "notList = [Öğrenciler,Bölümler,Numaralar,Dersler,VizeSonuçları,FinalSonuçları]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "ac43d000-d23b-41ed-a574-52999de0fb2e",
   "metadata": {},
   "outputs": [],
   "source": [
    " "
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
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
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

