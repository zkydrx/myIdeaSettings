# 说明
1. 新增了枚举类的格式，统一使用换行的格式。
    
        enum Week implements FUN
        {
            MON("星期一")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是工作日");
                        }
                    },
            TEU("星期二")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是工作日");
                        }
                    },
            WED("星期三")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是工作日");
        
                        }
                    },
            THU("星期四")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是工作日");
        
                        }
                    },
            FRI("星期五")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是工作日");
        
                        }
                    },
            STA("星期六")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是休息日");
        
                        }
                    },
            SUN("星期日")
                    {
                        @Override
                        public String doSomething(String str)
                        {
                            return str;
                        }
        
                        @Override
                        public void doWork()
                        {
                            System.out.print("是休息日");
        
                        }
                    };
            private String name;
        
            private Week(String name)
            {
                this.name = name;
            }
        
            public String getName()
            {
                return this.name;
            }
        
            public abstract void doWork();
        
        }