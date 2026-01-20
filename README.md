# Vale
Valentina's Updated Portfolio


my work sectionuhhhh

/* Make cards longer (taller + more breathing room) */
.work-item{
  background: #fff;
  color: #111;
  border: 1px solid rgba(0, 0, 0, 0.08);
  border-radius: 16px;

  padding: 24px;       /* a bit more internal spacing */
  padding-top: 200px;
  min-height: 350px;   /* ✅ makes them "longer" */
  display: flex;
  flex-direction: column;
  justify-content: space-between; /* keeps content nicely distributed */

  box-shadow: 0 1px 2px rgba(0,0,0,0.06);
  transition: transform 160ms ease, box-shadow 160ms ease, border-color 160ms ease;
}

/* Hover interaction */
.work-item:hover {
  transform: translateY(-2px);
  border-color: rgba(0, 0, 0, 0.12);
  box-shadow: 0 10px 24px rgba(0,0,0,0.10);
}

/* Typography + spacing */
.work-item-title {
  margin: 0 0 8px 0;
  font-size: 18px;
  line-height: 1.25;
  font-weight: 600;
  letter-spacing: -0.01em;
  color: #111;
}

.work-item-description {
  margin: 0;
  font-size: 14px;
  line-height: 1.5;
  color: rgba(17, 17, 17, 0.75);
}

/* Optional: make the whole card clickable if wrapped in <a> */
.work-item a {
  color: inherit;
  text-decoration: none;
  display: block;
}
