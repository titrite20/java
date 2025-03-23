import java.io.IOException;
import java.io.PrintWriter;
import javax.servlet.ServletException;
import javax.servlet.annotation.WebServlet;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

@WebServlet("/restaurant")
public class RestaurantServlet extends HttpServlet {
    private static final long serialVersionUID = 1L;

    protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
        response.setContentType("text/html");
        PrintWriter out = response.getWriter();
        out.println("<!DOCTYPE html>");
        out.println("<html>");
        out.println("<head>");
        out.println("<title>Restaurant</title>");
        out.println("<style>");
        out.println("body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }");
        out.println("header { background-color: #333; color: #fff; padding: 1em 0; text-align: center; }");
        out.println("nav ul { list-style-type: none; padding: 0; margin: 0; background-color: #444; text-align: center; }");
        out.println("nav ul li { display: inline; margin: 0 1em; }");
        out.println("nav ul li a { color: #fff; text-decoration: none; }");
        out.println("main { padding: 2em; text-align: center; }");
        out.println("footer { background-color: #333; color: #fff; text-align: center; padding: 1em 0; position: fixed; width: 100%; bottom: 0; }");
        out.println("</style>");
        out.println("</head>");
        out.println("<body>");
        out.println("<header>");
        out.println("<h1>Welcome to Our Restaurant</h1>");
        out.println("</header>");
        out.println("<nav>");
        out.println("<ul>");
        out.println("<li><a href='#'>Home</a></li>");
        out.println("<li><a href='#'>Menu</a></li>");
        out.println("<li><a href='#'>Contact</a></li>");
        out.println("</ul>");
        out.println("</nav>");
        out.println("<main>");
        out.println("<h2>Our Menu</h2>");
        out.println("<p>Here you can find our delicious dishes.</p>");
        out.println("</main>");
        out.println("<footer>");
        out.println("<p>&copy; 2025 Our Restaurant</p>");
        out.println("</footer>");
        out.println("</body>");
        out.println("</html>");
    }
}
