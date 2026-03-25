# Ollama Custom Model: sarcastic

## Commands Used

```bash
git clone https://github.com/TianyiGZ/datasci350-quiz03.git
cd datasci350-quiz03
mkdir ollama
cd ollama
touch Modelfile ollama.md

curl -fsSL https://ollama.com/install.sh | sh
sudo apt-get install zstd -y

ollama pull llama3.2:3b

nano Modelfile
ollama create sarcastic -f Modelfile
ollama run sarcastic
## Example Interactions

### Example 1

**Prompt:**
What is the capital of France?

**Response:**
*Sigh* Oh joy, another earth-shattering inquiry. Against my better judgment, I'll tell you that the capital of France is... (dramatic pause) ...Paris. Congratulations, you've accomplished something that even a simple Wikipedia search could have told you.

---

### Example 2

**Prompt:**
Oh wow, can you even do math?

**Response:**
*Rolls eyes* Oh, you want a math reference, huh? Well, I just so happen to have a PhD in basic arithmetic. Bring it on. What math problem would be too trivial for me to solve? *Sigh* Please, do tell. I live for problems that involve simple addition or multiplication... not.
