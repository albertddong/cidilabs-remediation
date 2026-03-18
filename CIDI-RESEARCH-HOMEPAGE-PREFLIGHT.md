# Cidi-Research Homepage Preflight Checklist

Use this checklist before pasting any `sample-user-code/homepage` template into Canvas.

## Required checks

1. Replace all bracketed placeholder text.
   Examples: course title, syllabus notes, button text, and any `[course link]` copy.

2. Remove all internal drafting notes.
   Delete lines like "DELETE this line," "Note for Albert," and any instructions meant for editors rather than students.

3. Verify every module link.
   Each `href="$CANVAS_OBJECT_REFERENCE$/modules/..."` should point to the correct module for that specific course.

4. Verify non-module links.
   Check syllabus links, page links, and any external references before publishing.

5. Confirm the image is correct for the course.
   Make sure the image belongs to the course, loads in Canvas, and is not an old sample asset.

6. Check image accessibility.
   If the image is decorative, `alt=""` is fine.
   If it conveys course information, replace it with meaningful `alt` text and remove presentation-only treatment.

7. Confirm the navigation section is complete.
   For `homepage-image.html`, make sure the placeholder CTA or button is replaced with a real working link before use.

8. Review visual spacing in Canvas after paste.
   Inline styles usually work, but check heading spacing, card wrapping, and link alignment in the actual Canvas page.

9. Test in Student View.
   Click every visible link and confirm students can reach the right destination.

10. Check mobile and narrow-width behavior.
    This matters most for `homepage-recommended.html`, since the flex card layout may wrap differently in tighter spaces.

11. Confirm consistency with the course's chosen homepage pattern.
    Use `simple`, `recommended`, or `image` intentionally rather than mixing structures ad hoc across courses.

12. Keep a clean source copy outside Canvas.
    Once a version is finalized, store the cleaned HTML separately so you do not have to reconstruct it from a pasted page later.
