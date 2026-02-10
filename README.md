```java
public class Developer {
    
    // About
    String name = "Basar Soyturk";
    String[] location = {"Istanbul 🇹🇷", "Porto 🇵🇹"};
    String status = "Senior Computer Engineering Student";
    
    // Currently
    String vibing = "Building stuff and learning";
    String[] deepDiving = {"Java", "Spring Boot"};
    String shipping = "Side projects";
    
    // Tech Stack
    class TechStack {
        String[] languages = {"Java", "C#", "TypeScript", "Python"};
        String[] frontend = {"React", "Tailwind CSS"};
        String[] backend = {"Spring Boot" ,".NET 8", "Flask", "tRPC"};
        String[] ai_ml = {"TensorFlow", "YOLOv8", "Computer Vision"};
        String[] tools = {"Docker", "PostgreSQL", "Git"};
    }
    
    // Projects
    class Projects {
        
        Project mediscanAI = new Project(
            "AI-powered skin cancer detection",
            new String[]{"Python", "TensorFlow", "React", "Flask"},
            "Trained neural network on HAM10000 dataset",
            "github.com/basarsy/mediscan-ai"
        );
        
        Project taskTrackApp = new Project(
            "Enterprise task management system",
            new String[]{".NET 8", "React", "PostgreSQL", "Docker"},
            "Real-time updates, background jobs, JWT Auth",
            "github.com/basarsy/TaskTrackApp"
        );
        
        Project carPal = new Project(
            "Digital garage & vehicle management",
            new String[]{"React", "tRPC", "Prisma", "PostgreSQL"},
            "Type-safe architecture with clean UI",
            "github.com/basarsy/carPal"
        );
        
        Project drive = new Project(
            "Traffic analysis with computer vision",
            new String[]{"YOLOv8", "DeepSORT", "OpenCV"},
            "Real-time vehicle detection & tracking",
            "github.com/basarsy/VehicleDetection"
        );
    }
    
    // Contact
    String linkedin = "linkedin.com/in/basar-soyturk";
    String email = "basarsoyturk03@gmail.com";
    String github = "github.com/basarsy";
    
    // Open to
    String[] openTo = {"Collaboration", "Interesting projects", "Learning opportunities"};
    
    public static void main(String[] args) {
        // Currently shipping code from two countries
        System.out.println("Let's build something together 🚀");
    }
}
```
