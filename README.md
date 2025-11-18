# 🌐 Multi-Threaded Client-Based Web Server with Real-Time Dashboard
This project is created for educational purposes to demonstrate Operating Systems concepts.

## 👨‍💻 Author

Created as a comprehensive demonstration of:
- Multi-threaded programming
- Socket programming
- Web server architecture
- Real-time data visualization
- OS concepts in practice

---

## 🎓 Learning Outcomes

By studying and running this project, you will understand:

1. **How web servers handle concurrent connections** using thread pools
2. **Thread synchronization** with locks to prevent race conditions
3. **Socket programming** for network communication
4. **Real-time data visualization** with modern web technologies
5. **Performance testing** and metrics collection
6. **Resource management** in multi-threaded applications

## 🐛 Troubleshooting

### Port Already in Use

```bash
# Kill process on port 8080
lsof -ti:8080 | xargs kill -9

# Kill process on port 5000
lsof -ti:5000 | xargs kill -9
```

### Import Errors

Make sure you're running from the project root directory:
```bash
cd /path/to/project
python3 run_all.py
```

### Missing Dependencies

```bash
pip install --upgrade flask matplotlib
```

## 📚 References

- [Python Socket Programming](https://docs.python.org/3/library/socket.html)
- [Python Threading](https://docs.python.org/3/library/threading.html)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Chart.js](https://www.chartjs.org/)
- [TailwindCSS](https://tailwindcss.com/)

---

**⚡ Ready to see it in action? Run `python3 run_all.py` and open http://localhost:5000!**
