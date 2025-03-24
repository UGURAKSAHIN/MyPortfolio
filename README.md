# Portfolio Website (ASP.NET Core MVC)

📌 Project Overview
This is a personal portfolio website built using ASP.NET Core MVC, following the Model-View-Controller (MVC) pattern. The project showcases my skills, projects, and professional experience with an interactive and responsive design.

🚀 Features
✅ Modern UI/UX – Built with HTML, CSS, and JavaScript for an engaging design.
✅ Dynamic Content – Uses C# and ASP.NET Core MVC to serve dynamic pages.
✅ Responsive Design – Works on desktop, tablet, and mobile devices.
✅ Contact Form – Visitors can send messages via a contact form.
✅ SEO Optimized – Proper meta tags for better search engine visibility.

🛠️ Technologies Used
ASP.NET Core MVC – Backend framework (C#)

Entity Framework Core – Database ORM (if used)

SQL Server / SQLite – Database management

HTML5, CSS3, JavaScript – Frontend development

Bootstrap – Responsive design framework

Visual Studio – Development environment

⚙️ Installation & Setup

1️⃣ Prerequisites

✅ .NET SDK (e.g., .NET 6/7)
✅ Visual Studio (with ASP.NET and Web Development workload)
✅ SQL Server or SQLite

2️⃣ Clone the Repository

# git clone https://github.com/yourusername/your-portfolio.git
# cd your-portfolio

3️⃣ Configure Database (If Applicable)

"ConnectionStrings": {
  "DefaultConnection": "Server=your_server;Database=your_db;User Id=your_user;Password=your_password;"
}

Run migrations (if using Entity Framework):

# dotnet ef database update

4️⃣ Run the Project

# dotnet run

🌍 Deployment

Azure App Service

GitHub Pages (for static parts)

Docker (for containerized deployment)

IIS (Internet Information Services)

# az webapp up --name my-portfolio-app --resource-group myResourceGroup
