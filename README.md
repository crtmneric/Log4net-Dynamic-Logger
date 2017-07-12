# Log4net-Dynamic-Logger
Here is a class with log4net logger u can use it without xml config file. Easy to integrate.
npm: Install-Package log4net -Version 2.0.8 
https://www.nuget.org/packages/log4net/

Usage:
 private static readonly ILog Log = LogManager.GetLogger(typeof(RollingFileAppender));
        public frmLogin()
        {
            InitializeComponent();
            Logger.Setup();
            Log.Info("System Started Succesfully");
            tmrAnimate.Enabled = true;
            DateTime now = DateTime.Now;     
            digitalGauge2.Text = now.ToString().Substring(10,5);
            tmrDate.Enabled = true;
        }




   Data Monitoring     |
-------------------------|
<img src="https://i.hizliresim.com/29JyjE.jpg" width="800">


