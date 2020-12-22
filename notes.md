# General

+ Continously dnb without stopping
+ half 6, half 7



# Setup

- **Font-Awesome**:Gotta install font-awesome icons through apt.

- **Direct Root login**: [Login prompt on terminal startup](https://superuser.com/questions/591321/execute-a-command-every-time-terminal-is-open)

- **Source tmux config**:
  ```bash
	tmux source-file ~/.tmux.conf
  ```
- **Create Shell vairables**:
  ```bash
	export varname=whatever
  ```
- **Move all files in a directory**:
  ```bash
	mv  -v ~/Downloads/* ~/Videos/
  ```

- **Autocorrelation Plot in Python**:
  ```python
      plt.acorr(data)
  ```
- **i3wm enable float for a particular application**:
   
  ```bash
     for_window [title="Authy"] floating enable
  ```
- **Kill all tmux server**:Do this or vim client-server keybindings wont work. 

  ```bash
     tmux kill-server
  ```
- **Tmux pane swapping program**: May need for keymappings in ~/.tmux/dev workflows.

  ```bash
     tmux swap-pane 
  ```
- **Installing i3-gaps problem**:Remember to lookup the autoreconf problem which says that the configure.ac is req  uired. 

- **Installing new font**:<https://jenciso.github.io/blog/how-setup-your-noto-color-emoji-fonts/>

- **vim set runtime paths as variables**:
  ```bash
     
     let $myvimdir = '/home/abc/vimfiles'
     
     :e $myvimdir/bundle/Vundle.vim
  ```
- **Installing Selenium**:<https://tecadmin.net/setup-selenium-chromedriver-on-ubuntu/>

- **Vim Open Another File in Current File Location**:
  ```bash
     :vs %:p:h/otherfile
  ```

- **Encrypt/Decrypt gpg file**:
  - **Encryption**:
    ```bash
       gpg -r sahil.singh@quantiphi.com -e pass
       rm -r pass
    ```
  - **Decryption**:
   ```bash
      gpg -r sahil.singh@quantiphi.com -d pass.gpg
   ```

- **Programming Productivity** :<https://medium.com/better-programming/practices-that-doubled-my-productivity-as-a-developer-70375a5f0c33>
  - Clear goal/task to accomplish at the end of the day helps you stay focussed

- **List Files Committed**: 
  ```bash
     git ls-tree --name-only HEAD
  ```
- **Printing Python Output to text File**

  ```python

     import sys 

     stdoutOrigin=sys.stdout 
     sys.stdout = open("log.txt", "w")
  ``` 
- **Swap File Location of Split**:

  ```
   <C-w><C-r>
  
  ```
## Stuff to Checkout

- [ ] **Github Backup of Modified Git Modules**
- [ ] **Jenkins**
- [ ] **Check Efficiency of AutoDiff in Julia**
- [ ] **GPG Problem Sollution**
- [ ] **Anki Style Flashcards in Terminal**
- [ ] **Nelder-Mead Algo for Alpha-Stable Pdf** 
- [ ] **Checkout Code for Pyflux GAS Implementation** 
- [ ] **Search Faster Code Method for Bayesia Op.**


# Finance

- **Dynamic correlation between assets**:Writes about estimating changing correlations between assets.<https://quantdare.com/to-be-or-not-to-be-correlated/>
- **Interesting Fractional Calculus book to check out**:Apparently talks about application of fractional calculus to financial data.<https://b-ok.asia/book/3307169/7a374c>
- **Portfolio Optimization course insights**:<https://www.coursera.org/learn/advanced-portfolio-construction-python#syllabus>:

  + Sharp style analysis to be used to find out industriwise allocation of funds
  + Factor GARCH model

- **Another Trading Course to Check Out**:<https://www.coursera.org/learn/machine-learning-trading-finance>
- **Constructing trading strategy ensembles by classifying market states**:<https://arxiv.org/abs/2012.03078>

## Stuff to Checkout

- [ ] **Trading team up Opportunity**:<https://www.reddit.com/r/algotrading/comments/k61gq8/looking_to_work_together/>
- [ ] **Try out Stochastic Fundamental/Noise Trader Model as Predictor**
- [ ] **Zerodha KYC Problem**
- [ ] **Backtesting**:<https://towardsdatascience.com/ai-in-finance-how-to-finally-start-to-believe-your-backtests-3-3-2f3b4d875842>
- [ ] **Portfolio Optimization Library**:<https://github.com/dcajasn/Riskfolio-Lib>
- [ ] **Necessity of Downloading Intraday Data Regularly**
- [ ] **Fundamentals for Long Term Prediction**
- [ ] **Find Data for Unlisted Stocks**
- [ ] **Butterworth Filter for Factor Variance**:Calculates standard deviation for normalizing 
        factors to put into ML model.
- [ ] **Butterworth Filter for GARCH Variance**
- [ ] **Another Trading Course to Check Out**:<https://www.coursera.org/learn/machine-learning-asset-management-alternative-data#syllabus>

# Math/Algo

- **Particle Filter**:<https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/12-Particle-Filters.ipynb>. Look into the resamapling methods mentioned and the code for that.

## Stuff to Checkout

- [ ] **Bootsraping**



# Day Checklist


- [ ] **Atulya Mail Attendance**
- [ ] **Get Chromedriver Working**: Get it working on your actual PC environment  
- [ ] **Complete the Course**
- [ ] **Stop Loss using Lower Timeframe Simulation**
- [ ] **GARCH Vol Estimate using Another Library**
- [ ] **ICICI Direct Login**
- [ ] **Tanya-chans study plan to Potato land**
