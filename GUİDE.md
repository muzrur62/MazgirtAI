# MazgirtAI - Anonymous AI Assistant (Local Desktop Version)

This project is an anonymous artificial intelligence assistant that runs locally on your desktop. It operates the Phi-3-mini model using 4-bit quantization, making it suitable for low RAM usage (even 4 GB is sufficient). The assistant understands and responds to questions in both Turkish and English.

## Features

*   **Anonymity:** No chat history is stored.
*   **Local Operation:** All operations are performed locally; no internet connection required.
*   **Low Resource Usage:** The Phi-3-mini model runs with 4-bit quantization.
*   **Multilingual Support:** Supports both Turkish and English questions.
*   **User-Friendly Interface:** Built with Tkinter, featuring a dark purple themed interface.
*   **Model Information:** Responds to queries like "I am based on Phi-3-mini".
*   **Security:** A securely developed, open-source application by the developer.

## Requirements

*   Python 3.8 or higher
*   `transformers` library (Hugging Face)
*   `torch` library (PyTorch)
*   `tkinter` (Usually comes with Python installation)

## Installation

1.  Extract the source code files from the `sourcecodes.zip` archive.
2.  Install the required libraries:

    ```bash
    pip install transformers torch
    ```

    > Note: `tkinter` usually comes bundled with Python. If needed, install it via your system administrator.

3.  Run the `mazgirtai.py` file:

    ```bash
    python mazgirtai.py
    ```

## Usage

1.  When the application starts, you'll see the message "MazgirtAI initializing...".
2.  If the model loads successfully, the message "✅ Ready! You can now ask your questions." will appear.
3.  Type your questions into the input field and click the "Send" button or press Enter.
4.  The assistant will provide a response based on your question.
5.  Special responses are given for identity questions (e.g., "What's your name?", "Who created you?").
6.  Upon closing the application, no chat history is saved.

## Code Structure

*   `mazgirtai.py`: Main Python file. Contains Tkinter GUI, Phi-3-mini model loading and processing.
    *   **Model Loading:** Uses `transformers` and `torch` to load the Phi-3-mini model with 4-bit quantization.
    *   **GUI:** Creates a dark purple themed interface using Tkinter.
    *   **Communication:** Processes user input, handles special identity queries, and sends regular questions to the model for processing.
    *   **Multilingual Support:** Utilizes Turkish and English keywords to respond to identity and model information queries.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```# MazgirtAI - Anonim Yapay Zeka Asistanı (Yerel Masaüstü Sürümü)

Bu proje, yerel masaüstü ortamında çalışabilen, anonim bir yapay zeka asistanıdır. Phi-3-mini modelini 4-bit nicemleme (quantization) ile çalıştırarak, düşük RAM kullanımına (4 GB bile yeterlidir) sahiptir. Asistan, hem Türkçe hem İngilizce soruları anlayabilir ve yanıtlar.

## Özellikler

*   **Anonimlik:** Sohbet geçmişi tutulmaz.
*   **Yerel Çalışma:** Tüm işlemler yerel olarak yapılır. İnternet bağlantısı gerekmez.
*   **Düşük Kaynak Kullanımı:** Phi-3-mini modeli 4-bit quantization ile çalıştırılır.
*   **Çok Dil Desteği:** Türkçe ve İngilizce soruları destekler.
*   **Kullanıcı Dostu Arayüz:** Tkinter kullanılarak geliştirilmiş, koyu mor temalı bir arayüz sunar.
*   **Model Bilgisi:** "Phi-3-mini tabanlıyım" gibi sorulara yanıt verir.
*   **Güvenlik:** Geliştirici tarafından güvenli şekilde oluşturulmuş, açık kaynak kodlu bir uygulamadır.

## Gereksinimler

*   Python 3.8 veya üzeri
*   `transformers` kütüphanesi (Hugging Face)
*   `torch` kütüphanesi (PyTorch)
*   `tkinter` (Genellikle Python ile birlikte gelir)

## Kurulum

1.  Projenin kaynak kodlarını `sourcecodes.zip` arşivinden çıkarın.
2.  Gerekli kütüphaneleri indirin:

    ```bash
    pip install transformers torch
    ```

    > Not: `tkinter` genellikle Python kurulumuyla birlikte gelir. Gerekirse sistem yöneticinizden yükleyin.

3.  `mazgirtai.py` dosyasını çalıştırın:

    ```bash
    python mazgirtai.py
    ```

## Kullanım

1.  Uygulama açıldığında, "MazgirtAI başlatılıyor..." mesajı görünür.
2.  Eğer model başarıyla yüklenirse, "✅ Hazır! Sorularınızı yazabilirsiniz." mesajı gösterilir.
3.  Sorularınızı giriş kutusuna yazın ve "Gönder" düğmesine tıklayın veya Enter tuşuna basın.
4.  Asistan, sorunuza göre yanıt verir.
5.  Kimlik soruları (örneğin: "Senin adın ne?", "Kim seni geliştirdi?") için özel yanıtlar verilir.
6.  Uygulama kapatıldığında, herhangi bir sohbet geçmişi saklanmaz.

## Kod Yapısı

*   `mazgirtai.py`: Ana Python dosyası. Tkinter GUI, Phi-3-mini model yükleme ve işlemeyi içerir.
    *   **Model Yükleme:** `transformers` ve `torch` kullanılarak Phi-3-mini modeli 4-bit quantization ile yüklenir.
    *   **GUI:** Tkinter kullanılarak koyu mor temalı bir arayüz oluşturulur.
    *   **İletişim:** Kullanıcı girdileri işlenir, kimlik soruları özel olarak yanıtlanır ve normal sorular model tarafından işlenir.
    *   **Çok Dil Desteği:** Türkçe ve İngilizce anahtar kelimelerle kimlik ve model bilgisi sorgulanabilir.

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır. [Lisans metni](LICENSE) dosyasına bakınız.
